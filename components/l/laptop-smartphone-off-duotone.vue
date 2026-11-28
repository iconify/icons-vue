<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="h4d0b7b7l"/><path class="lhnf5cc5a"/><path class="ayo73pbzj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:laptop-smartphone-off-duotone" /></template>
<style>
.ayo73pbzj {
  d: path("M2 2L22 22");
}

.h4d0b7b7l {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.7678 21.888C21.0493 22.577 20.0741 23 19 23H16C13.7909 23 12 21.209 12 19V13C12 12.726 12.0275 12.458 12.08 12.2L21.7678 21.888ZM15.558 9.024C15.7031 9.008 15.8506 9 16 9H19C21.2091 9 23 10.791 23 13V16.343C23 16.895 22.5523 17.343 22 17.343C21.7239 17.343 21.4739 17.231 21.2929 17.05L14.9638 10.721C14.7848 10.54 14.6743 10.292 14.6743 10.017C14.6743 9.504 15.0605 9.082 15.558 9.024Z");
  stroke: none;
}

.lhnf5cc5a {
  stroke-opacity: 0.4;
  d: path("M4 14V4M7.6569 2H18C19.1046 2 20 2.895 20 4M9 18H4C2.8954 18 2 17.105 2 16V14.5C2 14.224 2.2239 14 2.5 14H9");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
