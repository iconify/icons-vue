<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wu4p0xb0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:columnist" /></template>
<style>
.wu4p0xb0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5.5a3 3 0 1 0 6 0a3 3 0 1 0-6 0M2.5 16c0-2.5 2.5-4.5 5.5-4.5s5.5 2 5.5 4.5m-11 3h19m-5.289-1.16l.205-1.129a1.5 1.5 0 0 1 .415-.792L19.25 13.5a1.06 1.06 0 0 1 1.5 0a1.06 1.06 0 0 1 0 1.5l-2.629 2.629a1.5 1.5 0 0 1-.266.212l-.855.534a.521.521 0 0 1-.789-.535");
}

</style>
