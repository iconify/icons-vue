<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lzhngeb7n"/><path class="ea7j8zbqq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:desktop-and-laptop-sharp" /></template>
<style>
.ea7j8zbqq {
  d: path("M11.75 13h7.5v5.5h-7.5zm-1.5 8.25h10.5");
}

.lzhngeb7n {
  d: path("M4.75 3.75h13.5v6.5h-9.5v5h-6V3.75zm.75 11.5v6m-2 0h3.75");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
