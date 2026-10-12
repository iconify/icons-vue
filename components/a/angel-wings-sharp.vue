<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pjyc-cshb"/><path class="wgvmxbuvo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:angel-wings-sharp" /></template>
<style>
.pjyc-cshb {
  d: path("M10.5 9.75C8.25 6.75 5.25 6 2.75 6.5c0 2.25.75 3.75 2.25 4.25v2.667l2.5.833l.419 2.512l2.581.738Zm3 0c2.25-3 5.25-3.75 7.75-3.25c0 2.25-.75 3.75-2.25 4.25v2.667l-2.5.833l-.419 2.512l-2.581.738Z");
}

.wgvmxbuvo {
  d: path("M5 10.75h2L8.5 9.5m-1 4.75L8.75 14l.5-1M19 10.75h-2L15.5 9.5m1 4.75L15.25 14l-.5-1");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
