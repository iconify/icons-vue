<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="glje-utfp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:drag-drop" /></template>
<style>
.glje-utfp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 6.25v-2.5h2.5m1.25 0h2m2.25 0h2.5v2.5m0 1.25v2m-10.5-2v2m0 2.25v2.5h2.5m1.25 0h2m3.18-2.14l7.14 2.78q.93.36-.02.68l-2.6.86q-.95.32-1.27 1.27l-.86 2.6q-.32.95-.62 0l-2.4-7.6q-.3-.95.63-.59");
}

</style>
