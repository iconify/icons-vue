<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="sizysxbwg"/><path class="oqzpqv97y"/><path class="xszjfht3t"/><path class="qu0eyjbrg"/><path class="my5268blj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:clipboard-line-duotone" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.my5268blj {
  d: path("M9.5 6H14.5C15.3284 6 16 5.32843 16 4.5V3.5C16 2.67157 15.3284 2 14.5 2H9.5C8.67157 2 8 2.67157 8 3.5V4.5C8 5.32843 8.67157 6 9.5 6Z");
}

.oqzpqv97y {
  d: path("M8 14H16");
}

.qu0eyjbrg {
  d: path("M9 17.5H15");
}

.sizysxbwg {
  d: path("M16 4.00174C18.175 4.01385 19.3529 4.1103 20.1213 4.87868C21 5.75736 21 7.17157 21 10V16C21 18.8284 21 20.2426 20.1213 21.1213C19.2426 22 17.8284 22 15 22H9C6.17157 22 4.75736 22 3.87868 21.1213C3 20.2426 3 18.8284 3 16V10C3 7.17157 3 5.75736 3.87868 4.87868C4.64706 4.1103 5.82497 4.01385 8 4.00174");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.xszjfht3t {
  d: path("M7 10.5H17");
}

</style>
