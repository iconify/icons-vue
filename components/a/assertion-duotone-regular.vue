<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="sl7dojb6g"/><path class="dk2_9r6pl"/><path class="bq4e1jb8b"/><path class="o8od38cnm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:assertion-duotone-regular" /></template>
<style>
.bq4e1jb8b {
  d: path("m7 10 3 3 7 -7");
}

.dk2_9r6pl {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 18h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o8od38cnm {
  d: path("M4 18h16");
}

.sl7dojb6g {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("m7 10 3 3 7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
