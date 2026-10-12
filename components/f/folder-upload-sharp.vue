<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="kbd50tpon"/><path class="zh956wb4f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:folder-upload-sharp" /></template>
<style>
.kbd50tpon {
  d: path("M11.75 19.25h-9V4.75h7.1l.6.8L11.55 7l.6.8h9.1v4.75m-18.5-1.8h12");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zh956wb4f {
  d: path("M17.5 20.25v-6.5m-2.5 2.5l2.5-2.5l2.5 2.5");
}

</style>
