<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f0_kr6dzx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:alfalfa" /></template>
<style>
.f0_kr6dzx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 10v11.5M12 10c3-1.5 3-6.5 0-7.5c-3 1-3 6 0 7.5m0 0c-2-2.5-6-2.5-8 .5c2 2.5 6 2 8-.5m0 0c2-2.5 6-2.5 8 .5c-2 2.5-6 2-8-.5m0 7.5C10.5 15 7 15 5.5 17c1.5 2.5 5 2.5 6.5.5m0 0c1.5-2.5 5-2.5 6.5-.5c-1.5 2.5-5 2.5-6.5.5");
}

</style>
