<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="wkg5_f5aq"/><path class="wayhlnbcm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:apartment-block" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.wayhlnbcm {
  d: path("M7 6.5h2m2 0h2m2 0h2M7 10h2m2 0h2m2 0h2M7 13.5h2m2 0h2m2 0h2m-6.5 7.75v-3.5h3v3.5");
}

.wkg5_f5aq {
  width: 16.5px;
  height: 18.5px;
  x: 3.75px;
  y: 2.75px;
  rx: 1.5px;
}

</style>
