<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="auzd89bqy"/><path class="rq7bpabqc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:baby-bib-sharp" /></template>
<style>
.auzd89bqy {
  d: path("M8.25 3.75a3.75 3.75 0 0 0 7.5 0h.5l3.766.465L19.75 8v5.5a7.75 7.75 0 0 1-15.5 0V8l-.266-3.785L7.75 3.75Z");
}

.rq7bpabqc {
  d: path("M8.5 15.25L10 17.5h4l1.5-2.25");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
