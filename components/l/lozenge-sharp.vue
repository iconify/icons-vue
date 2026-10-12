<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="qjkurfbbn"/><path class="xe8sju2ir"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:lozenge-sharp" /></template>
<style>
.qjkurfbbn {
  d: path("m12.91 4l3.93 6.5l.91 1.5l-.91 1.5l-3.93 6.5l-.91 1.5l-.91-1.5l-3.93-6.5l-.91-1.5l.91-1.5L11.09 4L12 2.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xe8sju2ir {
  d: path("m12.39 8.64l1.62 2.72l.39.64l-.39.64l-1.62 2.72L12 16l-.39-.64l-1.62-2.72L9.6 12l.39-.64l1.62-2.72L12 8z");
}

</style>
