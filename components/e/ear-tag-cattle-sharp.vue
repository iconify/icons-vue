<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ux2u0rbkq"><path class="aska5gipy"/><path class="a5vfprbqd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:ear-tag-cattle-sharp" /></template>
<style>
.a5vfprbqd {
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M8.75 10.5h.01m3.99 0h.01m-3.51 5.75h.01m2.99 0h.01");
}

.aska5gipy {
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M8.25 5h7.5v9.75a5 5 0 0 1-10 0V5zm-2.5 3.25h-3.5l.9 1.2L4.313 11H5.75Zm10 0H20l-.9 1.2L17.938 11H15.75Zm3 4.75h2.5v4.25h-2.5z");
}

.ux2u0rbkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
}

</style>
