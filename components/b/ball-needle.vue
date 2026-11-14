<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-yj-obil"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:ball-needle" /></template>
<style>
.y-yj-obil {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m5.813 15.359l3.182-3.182a1.75 1.75 0 0 1 2.475 0l.353.353a1.75 1.75 0 0 1 0 2.475l-3.182 3.182a1.75 1.75 0 0 1-2.475 0l-.353-.353a1.75 1.75 0 0 1 0-2.475m5.833-3.005l7.779-7.779M7.404 13.768l2.828 2.828");
}

</style>
