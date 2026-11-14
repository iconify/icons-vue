<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="scy21mbzn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bamboo-grove" /></template>
<style>
.scy21mbzn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 21.5h19m-15 0v-6m0-2.75V6M12 21.5v-4m0-2.75V9m0-2.75V2.5m5.5 19V14m0-2.75V8m-11 1.5q-3 0-4-3.5q3 .5 4 3.5m11 1.75q3 0 4-3.5q-3 .5-4 3.5");
}

</style>
