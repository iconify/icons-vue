<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vbnidffgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:live-gift" /></template>
<style>
.vbnidffgq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4 9.5h16v11H4Zm8 0v11m0-11C10.5 6 7 6 7.5 8C7.75 9 10 9.5 12 9.5S16.25 9 16.5 8c.5-2-3-2-4.5 1.5");
}

</style>
