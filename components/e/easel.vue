<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="a9txrd2dq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:easel" /></template>
<style>
.a9txrd2dq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.75 6h10.5A1.75 1.75 0 0 1 19 7.75v5.5A1.75 1.75 0 0 1 17.25 15H6.75A1.75 1.75 0 0 1 5 13.25v-5.5A1.75 1.75 0 0 1 6.75 6M12 2.5V6m-3.5 9L6 21.5m9.5-6.5l2.5 6.5M12 15v6.5");
}

</style>
