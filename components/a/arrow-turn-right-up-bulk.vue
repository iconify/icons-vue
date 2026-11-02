<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m2n_px20w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-right-up-bulk" /></template>
<style>
.m2n_px20w {
  fill: currentColor;
  d: path("M14 16a.997.997 0 0 0 1-1V9.414l-3.293 3.293a.999.999 0 1 1-1.414-1.414l5-5a1 1 0 0 1 1.414 0l5 5a.999.999 0 1 1-1.414 1.414L17 9.414V15a3 3 0 0 1-3 3H3a1 1 0 0 1 0-2Z");
}

</style>
