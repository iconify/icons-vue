<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="syxd9nbtb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:grizzly-screen" /></template>
<style>
.syxd9nbtb {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m4.995 7.854l15.036 5.473M3.798 11.143l15.036 5.473M2.601 14.432l15.035 5.472M6.71 6.684l.697-1.361a1.5 1.5 0 0 1 1.164-.806l1.581-.182a1.5 1.5 0 0 1 1.452.71l.791 1.299a1.5 1.5 0 0 1 .129 1.293l-.438 1.202a1.5 1.5 0 0 1-1.922.896l-2.632-.958a1.5 1.5 0 0 1-.822-2.093m7.875 3.33l.24-.395A1.5 1.5 0 0 1 16.06 8.9l1.036-.033a1.5 1.5 0 0 1 1.303.68l.496.759a1.5 1.5 0 0 1 .154 1.333l-.086.235a1 1 0 0 1-1.282.598l-2.561-.933a1.045 1.045 0 0 1-.535-1.525");
}

</style>
