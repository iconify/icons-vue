<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jaf2uixoi"/><path class="bx9r1dbkq"/><path class="z0lfm0btn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:fume-hood-sharp" /></template>
<style>
.bx9r1dbkq {
  d: path("M7.75 9.75h9.5v8.5H6.75v-8.5z");
}

.jaf2uixoi {
  d: path("M3.75 6.75h16.5v14.5H3.75zm5.75 0v-4h5v4Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z0lfm0btn {
  d: path("M12 15.25c-.75-.6.75-1.15 0-1.75s.75-1.15 0-1.75");
}

</style>
