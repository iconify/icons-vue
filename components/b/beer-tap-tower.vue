<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dxcdtcc_h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:beer-tap-tower" /></template>
<style>
.dxcdtcc_h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 8.5h14.5A1.75 1.75 0 0 1 21 10.25A1.75 1.75 0 0 1 19.25 12H4.75A1.75 1.75 0 0 1 3 10.25A1.75 1.75 0 0 1 4.75 8.5M12 12za1.5 1.5 0 0 1 1.5 1.5v6A1.5 1.5 0 0 1 12 21a1.5 1.5 0 0 1-1.5-1.5v-6A1.5 1.5 0 0 1 12 12M6 2.5za1.38 1.38 0 0 1 1.375 1.495l-.292 3.508A1.087 1.087 0 0 1 6 8.5a1.087 1.087 0 0 1-1.083-.997l-.292-3.508A1.38 1.38 0 0 1 6 2.5m6 0za1.38 1.38 0 0 1 1.375 1.495l-.292 3.508A1.087 1.087 0 0 1 12 8.5a1.087 1.087 0 0 1-1.083-.997l-.292-3.508A1.38 1.38 0 0 1 12 2.5m6 0za1.38 1.38 0 0 1 1.375 1.495l-.292 3.508A1.087 1.087 0 0 1 18 8.5a1.087 1.087 0 0 1-1.083-.997l-.292-3.508A1.38 1.38 0 0 1 18 2.5M6 21h12");
}

</style>
