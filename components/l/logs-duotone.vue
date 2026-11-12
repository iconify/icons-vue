<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="njgkc8btq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:logs-duotone" /></template>
<style>
.njgkc8btq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M3 4h18M3 9h18M3 14h5m-5 5h5m4-2a5 5 0 1 0 10 0a5 5 0 0 0-10 0m5-2v2h2");
}

</style>
