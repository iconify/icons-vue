<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hjr3_vbwo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:booster-landing" /></template>
<style>
.hjr3_vbwo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 17V6c0-2 1-3.25 2.5-3.5c1.5.25 2.5 1.5 2.5 3.5v11Zm0-4.5l-4.5 9m9.5-9l4.5 9M12 17v4.5m-9 0h18");
}

</style>
