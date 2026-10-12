<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="leq-9tb_y"/><path class="i3ltlq0-c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:explosive-sharp" /></template>
<style>
.i3ltlq0-c {
  d: path("m12.2 7.32l.6 1.71l.19.57l.55-.26l1.63-.79l.54-.26l-.26.54l-.79 1.63l-.26.55l.57.19l1.71.6l.57.2l-.57.2l-1.71.6l-.57.19l.26.55l.79 1.63l.26.54l-.54-.26l-1.63-.79l-.55-.26l-.19.57l-.6 1.71l-.2.57l-.2-.57l-.6-1.71l-.19-.57l-.55.26l-1.63.79l-.54.26l.26-.54l.79-1.63l.26-.55l-.57-.19l-1.71-.6l-.57-.2l.57-.2l1.71-.6l.57-.19l-.26-.55l-.79-1.63l-.26-.54l.54.26l1.63.79l.55.26l.19-.57l.6-1.71l.2-.57z");
}

.leq-9tb_y {
  d: path("m13.59 3.84l6.57 6.57L21.75 12l-1.59 1.59l-6.57 6.57L12 21.75l-1.59-1.59l-6.57-6.57L2.25 12l1.59-1.59l6.57-6.57L12 2.25z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
