<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="lvrgauboa"/><circle class="dlwvvub8w"/><path class="iuu_5736s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:law-firm-sharp" /></template>
<style>
.dlwvvub8w {
  cx: 12px;
  cy: 7.75px;
  r: 1px;
}

.iuu_5736s {
  d: path("M7.5 13.5v5m9-5v5M10.75 21v-5.25h2.5V21");
}

.lvrgauboa {
  d: path("m3.55 9.9l7.65-5.8l.8-.6l.8.6l7.65 5.8l.8.6h-1.5v10.75H4.25V10.5h-1.5z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
