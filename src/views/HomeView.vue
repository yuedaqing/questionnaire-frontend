<template>
  <div class="home">home</div>
  {{ JSON.stringify(loginUserStore.loginUser) }}
</template>

<script lang="ts" setup>
import { useLoginUserStore } from "@/store/userStore";

const loginUserStore = useLoginUserStore();
</script>
