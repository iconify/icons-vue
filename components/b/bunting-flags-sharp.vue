<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="p9ux7l65h"/><path class="lx6_xkboz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bunting-flags-sharp" /></template>
<style>
.lx6_xkboz {
  d: path("m4.57 6.01l2.77 1.18l.55.23l-.38.46l-3.91 4.71l-.38.46l.07-.6l.66-6.07l.07-.6zm5.97 1.84h3.52l-.17.58l-1.72 5.84l-.17.58l-.17-.58l-1.72-5.84l-.17-.58zm6.12-.66l2.77-1.18l.55-.23l.07.6l.66 6.07l.07.6l-.38-.46l-3.91-4.71l-.38-.46z");
}

.p9ux7l65h {
  d: path("M2.75 5c6 4 12.5 4 18.5 0");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
