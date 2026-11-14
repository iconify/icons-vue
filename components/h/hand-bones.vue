<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b2you9jsq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hand-bones" /></template>
<style>
.b2you9jsq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.5 5v3M10 2.5V6m3.5-3v3.5m3.5-1v3M6.5 10.25V13M10 8.25v4.25m3.5-3.75v3.75m3.5-1.75v2.5m-10.5 2l2 5.25m1.5-5.75l.75 5.75m2.75-5.75l-.25 5.75m3.75-5l-1.5 5");
}

</style>
