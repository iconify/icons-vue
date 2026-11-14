<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="b-_bu9rtv"/><path class="bwea0cckg"/><path class="zdqh56bls"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:archway" /></template>
<style>
.b-_bu9rtv {
  d: path("M5.625 3.5h12.75A2.625 2.625 0 0 1 21 6.125v12.25A2.625 2.625 0 0 1 18.375 21H5.625A2.625 2.625 0 0 1 3 18.375V6.125A2.625 2.625 0 0 1 5.625 3.5");
}

.bwea0cckg {
  d: path("M8 21v-7a4 4 0 0 1 8 0v7");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zdqh56bls {
  d: path("M12 6.5za1.415 1.415 0 0 1 1.383 1.711l-.173.811A1.24 1.24 0 0 1 12 10a1.24 1.24 0 0 1-1.21-.978l-.173-.811A1.415 1.415 0 0 1 12 6.5");
}

</style>
