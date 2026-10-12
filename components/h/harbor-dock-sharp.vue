<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="m-5thdbpl"/><path class="isd6rub5e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:harbor-dock-sharp" /></template>
<style>
.isd6rub5e {
  d: path("M12 5.5c1.75 1.5 2.5 4 2.5 7.25v5.75h-5v-5.75C9.5 9.5 10.25 7 12 5.5Z");
}

.m-5thdbpl {
  d: path("M2.75 3.25v18h18.5v-18M2.75 7.5h3m15.5 0h-3");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
