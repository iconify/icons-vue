<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="rh2140hgr"/><path class="osg19zjgn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:file-js-sharp" /></template>
<style>
.osg19zjgn {
  d: path("M13.75 2.75v5.5h5.5m-9 2.75v5.5a1.5 1.5 0 0 1-2.75.85m8.75-5.6l-.545-.784l-.955.034a1.6 1.6 0 0 0-.25 3.2l.5.1a1.6 1.6 0 0 1-.25 3.2l-.955.034l-.545-.784");
}

.rh2140hgr {
  d: path("M13.75 2.75h-9v18.5h14.5v-13Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
