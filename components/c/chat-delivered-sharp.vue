<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="vgu78uopy"/><path class="um4rs3boc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:chat-delivered-sharp" /></template>
<style>
.um4rs3boc {
  d: path("m6.75 10.5l2 2l4-4.25m-1 3.75l.5.5l4-4.25");
}

.vgu78uopy {
  d: path("M2.75 6.25v-2.5h18.5v14H12.5L8 20.85l-1.25 1v-4.1h-4v-2.5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
