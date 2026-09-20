<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c6kztyquz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:looks-6-sharp" /></template>
<style>
.c6kztyquz {
  fill: currentColor;
  d: path("M11 11V9h3V7H9v10h6v-6zm0 2h2v2h-2zm-8 8V3h18v18z");
}

</style>
