<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xq3tlublz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:glossary-dev" /></template>
<style>
.xq3tlublz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12 6.5Q9 4.25 3 5v13.5q6-.75 9 1.5m0-13.5q3-2.25 9-1.5v13.5q-6-.75-9 1.5m0-13.5V20M5.75 9.5h3.5M5.75 13h3.5m5.5-3.5h3.5m-3.5 3.5h3.5");
}

</style>
