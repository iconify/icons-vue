<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yyu8fktwf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dates-bowl" /></template>
<style>
.yyu8fktwf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.25 9.25a3.5 1.75-30 1 1 6.06-3.5a3.5 1.75-30 1 1-6.06 3.5m7.44-3.5a3.5 1.75 30 1 1 6.06 3.5a3.5 1.75 30 1 1-6.06-3.5m-9.69 7h18c0 4.5-3.75 7.5-9 7.5s-9-3-9-7.5");
}

</style>
