<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xxpf3vd6e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:briefcase-off" /></template>
<style>
.xxpf3vd6e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.4 6.5h13.1v13.1m-7.4.4H2.5V8.4M9 6.5v-2a1 1 0 0 1 1-1h4a1 1 0 0 1 1 1v2m-11.5-1l16 16");
}

</style>
