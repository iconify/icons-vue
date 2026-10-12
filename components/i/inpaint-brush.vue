<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b7ru3r85p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:inpaint-brush" /></template>
<style>
.b7ru3r85p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m20.17 3.17l.66.66q.42.42.02.87l-5.95 6.6q-.4.45-.82.03l-1.41-1.41q-.42-.42.03-.82l6.6-5.95q.45-.4.87.02m-9.67 8.08l2.25 2.25c-.4 2.9-2.4 4.6-6 4.4c.6-3.4 1.6-6.1 3.75-6.65m-7.75 3v1.5m0 3.25v.25a2 2 0 0 0 2 2H5m3.25 0h1.5");
}

</style>
