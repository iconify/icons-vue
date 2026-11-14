<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vr3gzib-l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:dental-education" /></template>
<style>
.vr3gzib-l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M9.5 2.5C7.5 2.5 6.75 4 6.75 6c0 1.75.75 3 1 4.25l.5 2c.25 1 1.25 1 1.5 0L10.5 10c.25-.75 2.75-.75 3 0l.75 2.25c.25 1 1.25 1 1.5 0l.5-2c.25-1.25 1-2.5 1-4.25c0-2-.75-3.5-2.75-3.5c-1 0-1.5.75-2.5.75s-1.5-.75-2.5-.75ZM2.5 15c3 0 6.5 1 9.5 2.5c3-1.5 6.5-2.5 9.5-2.5v5c-3 0-6.5.5-9.5 1.5c-3-1-6.5-1.5-9.5-1.5Zm9.5 2.5v4");
}

</style>
