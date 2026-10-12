<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kqf0pp7ls"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:candy-cane-sharp" /></template>
<style>
.kqf0pp7ls {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.75 19.75V8a5.25 5.25 0 0 1 10.5 0v3h-3V8a2.25 2.25 0 0 0-4.5 0v13.25h-3zm.7-14.38l2.6 1.51M13 2.75v3m4.55-.38l-2.6 1.51m-7.2 4.87l3-1.5m-3 5.75l3-1.5m-3 5.6l3-1.5");
}

</style>
