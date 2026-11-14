<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ip53i7_5x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:campfire-marshmallow" /></template>
<style>
.ip53i7_5x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m15.194 10.394l-3.04-3.04l4.95-4.95l4.242 4.242l-3.536 3.536M3.5 20.25L14.25 9.5m4.25 12c-2 0-3.25-1.5-3.25-3.25s1.25-3 1.75-4.5c.75 1 1.25 1.75 1.5 2.75c.5-.75.75-1.25 1-1.75c1.25 1 2.25 2.25 2.25 3.75c0 1.75-1.5 3-3.25 3Z");
}

</style>
