<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="uudyrgb2a"/><path class="ko7vgklqj"/><path class="rki_rg93o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:funicular-outline-regular" /></template>
<style>
.ko7vgklqj {
  d: path("m4 20 4 -4h6l-4 4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rki_rg93o {
  d: path("m12 12 4 -4h6l-4 4Z");
}

.uudyrgb2a {
  d: path("M2 21 21 2");
}

</style>
