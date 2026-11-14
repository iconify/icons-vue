<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="zghn0vbbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gharial" /></template>
<style>
.zghn0vbbd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M3 17c-.5-4-.25-7.25 2-8.25c.5-2.25 3.5-2.25 4 0c.25 1.25 1 1.75 2.5 1.75h5.75a2.5 2.5 0 1 1 0 2.75H10C8 13.25 7 15 7 17m-.25-7h.01");
}

</style>
