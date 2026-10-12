<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="sc7posbsa"/><path class="h84qtj2uh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:double-glazing-sharp" /></template>
<style>
.h84qtj2uh {
  d: path("M2.75 6.25h14v15h-14zm3.5 8l3.5-3.5m-3.5 7l6.5-6.5");
}

.sc7posbsa {
  d: path("M6.25 6.25v-3.5h15v15h-4.5");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
