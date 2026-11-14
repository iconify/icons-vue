<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hdw-qd17i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:banner-tow-plane" /></template>
<style>
.hdw-qd17i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M17.1 11H2.5V2.5h17V11h-1.7M6 6.75h10M11 11l1.464 2.733M14.75 18h6.75M19 18l-2.25-3.5M19 18l-2.25 3.5m-2-5v3");
}

</style>
