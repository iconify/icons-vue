<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="x2cwu0gfd"><path class="o7-x7jbpd"/><path class="sib9sdbju"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:haveli-sharp" /></template>
<style>
.o7-x7jbpd {
  d: path("M4.25 6.5a1.5 3 0 0 1 3 0m9.5 0a1.5 3 0 0 1 3 0M9.5 6.5a2.5 3 0 0 1 5 0m-11.25 0h17.5v14.75H3.25z");
}

.sib9sdbju {
  d: path("M5.75 12.5V9.75h2.5v2.75Zm10 0V9.75h2.5v2.75ZM9.5 21.25v-5a2.5 2.5 0 0 1 5 0v5Z");
}

.x2cwu0gfd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 2;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
