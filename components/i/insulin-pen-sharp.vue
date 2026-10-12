<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="mtjmhpc7u"/><path class="slesxdbfy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:insulin-pen-sharp" /></template>
<style>
.mtjmhpc7u {
  d: path("m3.5 20.5l2.12-2.12m2.65.89l8.14-8.14l.88-.88l-.88-.88l-1.78-1.78l-.88-.88l-.88.88l-8.14 8.14l-.88.88l.88.88l1.78 1.78l.88.88zm3.01-6.55l2.12-2.12");
}

.slesxdbfy {
  d: path("m17.64 8.83l1.42-1.41l.88-.89l-.88-.88l-.71-.71l-.88-.88l-.89.88l-1.41 1.42l-.89.88l.88.88l.72.72l.88.88z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
