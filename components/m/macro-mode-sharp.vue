<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><circle class="dbgvcxwad"/><path class="f0upgebrs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:macro-mode-sharp" /></template>
<style>
.dbgvcxwad {
  cx: 12px;
  cy: 12px;
  r: 9.25px;
}

.f0upgebrs {
  d: path("m9.32 7.99l.61.52l.57.49l.45-.6l.6-.8L12 7l.45.6l.6.8l.45.6l.57-.49l.61-.52l.57-.49v4l-.59.46l-2.07 1.58L12 14l-.59-.46l-2.07-1.58l-.59-.46v-4zM12 14v3.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
