<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pm3ghbcin"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:accessible-toilet-sharp" /></template>
<style>
.pm3ghbcin {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3.75 2.75h5V8h-5zm0 8.5h11.5v4.6l-4.5.9l.75 4.5h-6l.75-4.5l-2.5-1.25zm16-3.5v9.5");
}

</style>
