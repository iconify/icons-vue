<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lhbkqab6l"/><path class="fbm7dgb5u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:family-home-sharp" /></template>
<style>
.fbm7dgb5u {
  d: path("m12 16.5l-2.5-2.4a1.6 1.6 0 0 1 2.5-2a1.6 1.6 0 0 1 2.5 2Z");
}

.lhbkqab6l {
  d: path("M4.25 10.6v-.921l.7-.599l5.75-4.9L12 3.068l1.3 1.112l5.75 4.9l.7.599V21.25H4.25v-2Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
