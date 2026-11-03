<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="xxcb1mbaj"/><path class="fv95khbzf"/><path clip-rule="evenodd" class="xchqowbfg"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:file-image-duotone" /></template>
<style>
.fv95khbzf {
  d: path("M20 8L14 2M14 2L14 5C14 6.6569 15.3431 8 17 8L20 8");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.xchqowbfg {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5 17L9.2355 12.7645C9.6921 12.3079 10.3895 12.1948 10.967 12.4835L19 16.5L19 18C19 19.6569 17.6569 21 16 21L8 21C6.3431 21 5 19.6569 5 18L5 17ZM10.5 7C10.5 7.8284271247 9.8284271247 8.5 9 8.5C8.1715728753 8.5 7.5 7.8284271247 7.5 7C7.5 6.1715728753 8.1715728753 5.5 9 5.5C9.8284271247 5.5 10.5 6.1715728753 10.5 7Z");
  stroke: none;
}

.xxcb1mbaj {
  fill: currentColor;
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M14 1C14.2652 1 14.5195 1.1054 14.707 1.293L20.707 7.293C20.8946 7.4805 21 7.7348 21 8V18C21 20.7614 18.7614 23 16 23H8C5.2386 23 3 20.7614 3 18V6C3 3.2386 5.2386 1 8 1H14Z");
  stroke: none;
}

</style>
