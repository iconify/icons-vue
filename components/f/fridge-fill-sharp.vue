<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j6b87tb1q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:fridge-fill-sharp" /></template>
<style>
.j6b87tb1q {
  fill: currentColor;
  d: path("M4 9V3a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v6Zm12-3a1 1 0 0 0-2 0v1a1 1 0 0 0 2 0ZM4 11h16v10a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1Zm12 6v-3a1 1 0 0 0-2 0v3a1 1 0 0 0 2 0");
}

</style>
