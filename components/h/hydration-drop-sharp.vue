<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="d-rurw9-j"/><path class="y_k37zb5h"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:hydration-drop-sharp" /></template>
<style>
.d-rurw9-j {
  d: path("M12 2.75C15.75 7 18.5 10.5 18.5 14a6.5 6.5 0 0 1-13 0c0-3.5 2.75-7 6.5-11.25Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.y_k37zb5h {
  d: path("m8.5 14.5l1.75-1.141L12 14.5l1.75 1.141L15.5 14.5a3.5 3.5 0 0 1-7 0Z");
}

</style>
