<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="e5i3r3bae"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:jet-lag" /></template>
<style>
.e5i3r3bae {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M11 5.5a7.5 7.5 0 1 0 7.75 9a6 6 0 0 1-7.75-9m3.25-2.75h3.25L14.25 6.5h3.25m1 2.25h2.75l-2.75 3h2.75");
}

</style>
