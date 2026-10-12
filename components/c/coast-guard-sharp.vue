<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="b-01clbsq"/><path class="u4n1axbla"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:coast-guard-sharp" /></template>
<style>
.b-01clbsq {
  d: path("m11.65 2.88l.35-.131l.35.131l6.5 2.4l.652.244l-.002.696v5.28c0 4.75-3.25 8.25-7.5 9.75c-4.25-1.5-7.5-5-7.5-9.75V6.22l-.002-.696l.652-.244Z");
}

.u4n1axbla {
  d: path("m7.45 12.09l9.35-4.28l.45-.21v3l-.45.21l-8.6 3.93l-.45.21l-.14-.48l-.47-1.69L7 12.3zm2.05 4.96l7.7-3.6");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
