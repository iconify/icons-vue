<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hhdhh4b-j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-4-fill" /></template>
<style>
.hhdhh4b-j {
  fill: currentColor;
  d: path("M3 21a1 1 0 0 1 0-2h1V6a3 3 0 0 1 3-3h6a3 3 0 0 1 3 3v2h1a3 3 0 0 1 3 3v8h1a1 1 0 0 1 0 2ZM9 9h2a1 1 0 0 0 0-2H9a1 1 0 0 0 0 2m9 10v-8a1 1 0 0 0-1-1h-1v9Zm-9-6h2a1 1 0 0 0 0-2H9a1 1 0 0 0 0 2");
}

</style>
