<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="ufbeocnbu"/><path class="ht0xc7whw"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:edit-x-sharp" /></template>
<style>
.ht0xc7whw {
  d: path("M10.7 15.65L8.35 13.3l-.42-.42l-.31.51l-2.31 3.83l-.31.51l.42.42l.43.43l.42.42l.51-.31l3.83-2.31l.51-.31zm5.37-4.53l-3.19-3.19");
}

.ufbeocnbu {
  d: path("m20.31 5.46l-1.77-1.77l-.71-.71l-.71.71l-8.48 8.48l-.71.71l.71.71l1.77 1.77l.71.71l.71-.71l8.48-8.48l.71-.71z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
