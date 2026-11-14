<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="b3hoyuzgk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:figure-eight-tracks" /></template>
<style>
.b3hoyuzgk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M12.722 10.901A9.6 9.6 0 0 1 12 9.5c-2.5-6-9.5-6.5-9.5 0s7 6 9.5 0s9.5-6.5 9.5 0c0 1.027-.175 1.88-.479 2.563M15.5 13.5h2.75v2.25l2.75 1v1.75h-5.5Zm-.5 7.75h6.5");
}

</style>
