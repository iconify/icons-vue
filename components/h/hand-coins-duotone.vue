<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path clip-rule="evenodd" class="v-ztenk8w"/><path class="e6y_ys-yk"/><path class="qyxj4hipy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hand-coins-duotone" /></template>
<style>
.e6y_ys-yk {
  fill: currentColor;
  d: path("M2.3293 15.5583L6.2619 12.0023C6.8113 11.5074 7.4541 11.1273 8.1525 10.8845C8.7906 10.6641 9.461 10.5516 10.136 10.5516C10.5512 10.5516 10.9652 10.5941 11.3716 10.6785L12.9284 10.9974L13.4629 10.4628C14.0258 9.9001 14.7891 9.5839 15.585 9.5839C17.2425 9.5839 18.5861 10.9275 18.5861 12.585C18.5861 13.3809 18.2699 14.1443 17.7071 14.7071L13.7071 18.7071C13.1544 19.2518 12.4688 19.6423 11.7184 19.8399C11.321 19.9464 10.9114 20.0002 10.5 20L5.8284 20C5.5632 20.0001 5.3089 20.1055 5.1213 20.2929L3.7071 21.7071C3.5196 21.8946 3.2652 22 3 22C2.4477 22 2 21.5523 2 21L2 16.3C2 16.0173 2.1196 15.7478 2.3293 15.5583Z");
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qyxj4hipy {
  d: path("M3 14L3 22");
}

.v-ztenk8w {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  fill-rule: evenodd;
  d: path("M22 4.5C22 6.433 20.433 8 18.5 8C16.567 8 15 6.433 15 4.5C15 2.567 16.567 1 18.5 1C20.433 1 22 2.567 22 4.5ZM9.5 5.5C9.5 7.433 7.933 9 6 9C4.067 9 2.5 7.433 2.5 5.5C2.5 3.567 4.067 2 6 2C7.933 2 9.5 3.567 9.5 5.5Z");
  stroke: none;
}

</style>
