<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="a4dj3q77k"/><path class="dti7o1mke"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:feed-reader" /></template>
<style>
.a4dj3q77k {
  d: path("M2.5 3.5h19v13h-19Zm9.5 13v4m-4 0h8M8 13h.01");
}

.dti7o1mke {
  d: path("M8 9.5a3.5 3.5 0 0 1 3.5 3.5M8 6.5a6.5 6.5 0 0 1 6.5 6.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
