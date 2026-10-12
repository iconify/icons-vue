<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l6p6n6b-e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chimney" /></template>
<style>
.l6p6n6b-e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.75 20.65V18.1q0-.6.56-.81l9.13-3.46q.56-.21.56-.81V9.1q0-.6.6-.6h3.3q.6 0 .6.6v2.22q0 .6.56.39l2.63-1q.56-.21.56.39v9.55q0 .6-.6.6H3.35q-.6 0-.6-.6M14 6.75c-1.25-1 1.25-2 0-4m2.75 4c-1.25-1 1.25-2 0-4");
}

</style>
