<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="ww9xu0bkc"/><path class="ixid0gf9s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-coins-fill" /></template>
<style>
.ixid0gf9s {
  d: path("M3 14L3 22M3 16.3L6.9326 12.7441C8.0716 11.7143 9.6664 11.35 11.171 11.6582L13.255 12.085M11.17 14.17L14.17 11.17C14.9511 10.389 16.219 10.389 17 11.17C17.7811 11.9511 17.7811 13.219 17 14L13 18C12.4 18.6 11.5 19 10.5 19L5.8284 19C5.2985 19 4.7892 19.2108 4.4142 19.5858L3 21");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.ww9xu0bkc {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M3 16.3L6.9326 12.7441C8.0716 11.7143 9.6664 11.35 11.171 11.6582L13.255 12.085L14.17 11.17C14.9511 10.389 16.219 10.389 17 11.17C17.7811 11.9511 17.7811 13.219 17 14L13 18C12.4 18.6 11.5 19 10.5 19L5.8284 19C5.2985 19 4.7892 19.2108 4.4142 19.5858L3 21ZM22 4.5C22 6.433 20.433 8 18.5 8C16.567 8 15 6.433 15 4.5C15 2.567 16.567 1 18.5 1C20.433 1 22 2.567 22 4.5ZM9.5 5.5C9.5 7.433 7.933 9 6 9C4.067 9 2.5 7.433 2.5 5.5C2.5 3.567 4.067 2 6 2C7.933 2 9.5 3.567 9.5 5.5Z");
  stroke: none;
}

</style>
