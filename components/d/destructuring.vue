<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f6fyyjb-t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:destructuring" /></template>
<style>
.f6fyyjb-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8 3.5c-2 0-2.5 1-2.5 3v3C5.5 11 4.75 12 3 12c1.75 0 2.5 1 2.5 2.5v3c0 2 .5 3 2.5 3m4.75-17h.5A1.75 1.75 0 0 1 15 5.25v.5a1.75 1.75 0 0 1-1.75 1.75h-.5A1.75 1.75 0 0 1 11 5.75v-.5a1.75 1.75 0 0 1 1.75-1.75m5.5 6.5h.5a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 18.75 14h-.5a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 18.25 10m-5 7h.5a1.75 1.75 0 0 1 1.75 1.75v.5A1.75 1.75 0 0 1 13.75 21h-.5a1.75 1.75 0 0 1-1.75-1.75v-.5A1.75 1.75 0 0 1 13.25 17");
}

</style>
