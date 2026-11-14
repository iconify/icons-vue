<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="k_uw0ybah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:fog-machine-stage" /></template>
<style>
.k_uw0ybah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.625 14h12.75A2.625 2.625 0 0 1 21 16.625v1.75A2.625 2.625 0 0 1 18.375 21H5.625A2.625 2.625 0 0 1 3 18.375v-1.75A2.625 2.625 0 0 1 5.625 14M9.5 14L8 10.5h8L14.5 14m-8 3.5H11M9 7.75C7.5 6 6 7.5 4.5 4.5M12 7.75C10.5 6 13.5 5 12 3m3 4.75C16.5 6 18 7.5 19.5 4.5");
}

</style>
