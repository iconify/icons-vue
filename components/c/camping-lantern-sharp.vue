<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="pdk5-d7sa"/><path class="dldwtfbhb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:camping-lantern-sharp" /></template>
<style>
.dldwtfbhb {
  d: path("M12 15.5h-1.5V13l1.5-1.25L13.5 13v2.5zm-5.25 2.25h10.5v3.5H6.75z");
}

.pdk5-d7sa {
  d: path("M9.5 5.5a2.5 2.5 0 0 1 5 0M7.61 8.09l1.03-1.93L9 5.5h6l.36.66l1.03 1.93l.36.66h-9.5zm.14.66h8.5v9h-8.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
