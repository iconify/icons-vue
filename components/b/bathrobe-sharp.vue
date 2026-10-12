<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="inr0gachh"/><path class="ekyneyzeq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:bathrobe-sharp" /></template>
<style>
.ekyneyzeq {
  d: path("m9 3l3 7l3-7m-3 7v1.75m-6 0h12V14H6zM11 14l-1 3.5m3-3.5l1 3.5");
}

.inr0gachh {
  d: path("M10 2.75h5.25l1.08.63l2.59 1.49L20 5.5l.22 1.23l.81 4.54l.22 1.23l-1.22.28l-.81.19l-1.22.28v8H6v-8l-1.22-.28l-.81-.19l-1.22-.28l.22-1.23l.81-4.54L4 5.5l1.08-.63l2.59-1.49l1.08-.63z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
