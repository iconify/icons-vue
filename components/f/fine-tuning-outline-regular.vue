<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="iaozfqbuj"/><path class="s09hy0b0y"/><path class="gyjefyijl"/><path class="c7z9o8buo"/><path class="tldtqlb3m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fine-tuning-outline-regular" /></template>
<style>
.c7z9o8buo {
  d: path("M7 15h10");
}

.gyjefyijl {
  d: path("M14 9v4");
}

.iaozfqbuj {
  d: path("M14.5 4H17a3 3 0 0 1 3 3v10a3 3 0 0 1 -3 3H7a3 3 0 0 1 -3 -3V8l4 -4h2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.s09hy0b0y {
  d: path("M7 11h10");
}

.tldtqlb3m {
  d: path("M10 13v4");
}

</style>
