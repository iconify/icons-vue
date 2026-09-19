<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="dcx47rbia"/><path class="m7uapvbhj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-monotone:flag-for-flag-panama" /></template>
<style>
.dcx47rbia {
  fill: currentColor;
  d: path("m18.418 17.004l-1.168-3.687l-1.135 3.687h-3.782l3.025 2.395l-1.146 3.751l3.038-2.307l3.038 2.307l-1.146-3.751l3.025-2.395zm25.294 31.713l3.038-2.307l3.038 2.307l-1.146-3.751l3.025-2.396h-3.749l-1.168-3.687l-1.135 3.687h-3.782l3.025 2.396z");
}

.m7uapvbhj {
  fill: currentColor;
  d: path("M32 2C15.432 2 2 15.432 2 32s13.432 30 30 30s30-13.432 30-30S48.568 2 32 2m0 58V32H4C4 16.561 16.561 4 32 4v28h28c0 15.439-12.561 28-28 28");
}

</style>
