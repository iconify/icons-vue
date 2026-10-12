<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="jvqy09btk"/><path class="gzp7-mhce"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-broken-sharp" /></template>
<style>
.gzp7-mhce {
  d: path("M13.75 2.75v5.5h5.5m-14.5 6.5L8 16.25L11.25 14l3.25 2.25l4.75-2v6.5H4.75v-2.5Z");
}

.jvqy09btk {
  d: path("M13.75 2.75h-9v8.75L8 13l3.25-2.25L14.5 13l4.75-2V8.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
