<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y-nhnn4vd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:discount-bogo" /></template>
<style>
.y-nhnn4vd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M18 7.25V3H7L3.5 7.5l1.75 2.25M12.2 19h-1.7L7 14.5l3.5-4.5h11v5.2M7 7.5h.01m3.74 7h.01M18 15v6m-3-3h6");
}

</style>
