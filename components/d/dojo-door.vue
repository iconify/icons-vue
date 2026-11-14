<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aw1p9tbth"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dojo-door" /></template>
<style>
.aw1p9tbth {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.75 5.75l1.225-1.574A1.75 1.75 0 0 1 7.356 3.5h9.288a1.75 1.75 0 0 1 1.381.676L19.25 5.75A1.394 1.394 0 0 1 18.15 8H5.85a1.394 1.394 0 0 1-1.1-2.25M4 8v13.5h16V8m-8 0v13.5M9.25 13v3.5m5.5-3.5v3.5");
}

</style>
