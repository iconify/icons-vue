<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="d8z1r1beo"/><path class="wzx0dxb2r"/><path class="s09hy0b0y"/><path class="c7z9o8buo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:index-rebuild-outline-thin" /></template>
<style>
.c7z9o8buo {
  d: path("M7 15h10");
}

.d8z1r1beo {
  d: path("M15 5h3a3 3 0 0 1 3 3v9a3 3 0 0 1 -3 3H6a3 3 0 0 1 -3 -3V8a3 3 0 0 1 3 -3h3");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.s09hy0b0y {
  d: path("M7 11h10");
}

.wzx0dxb2r {
  d: path("m12 2 3 3 -3 3");
}

</style>
