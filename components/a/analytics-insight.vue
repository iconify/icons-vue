<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="be9pzsuua"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:analytics-insight" /></template>
<style>
.be9pzsuua {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 2.75a6.75 6.75 0 0 0-4 12.2v1.55A1.5 1.5 0 0 0 9.5 18h5a1.5 1.5 0 0 0 1.5-1.5v-1.55a6.75 6.75 0 0 0-4-12.2m-2.25 18.5h4.5m-4.75-9v-1.5m2.5 1.5v-4.5m2.5 4.5V9.5");
}

</style>
