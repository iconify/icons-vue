<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="h6y8oe5qp"/><path class="j3kjqcbth"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:confession-booth-sharp" /></template>
<style>
.h6y8oe5qp {
  d: path("M12 6.5V2.75M10.75 4h2.5M4 20.65V8.75H2.75V6.5h18.5v2.25H20v12.5H4z");
}

.j3kjqcbth {
  d: path("M9.5 21.25V12.5a2.5 2.5 0 0 1 5 0v8.75M5.75 12h2m-2 2.25h2m-2 2.25h2m8.5-4.5h2m-2 2.25h2m-2 2.25h2");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
