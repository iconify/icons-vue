<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mr1uq9olq"/><path class="a5nbbg36f"/><path class="uudyrgb2a"/><path class="ko7vgklqj"/><path class="rki_rg93o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:funicular-duotone-thin" /></template>
<style>
.a5nbbg36f {
  fill: currentColor;
  d: path("m12 12 4 -4h6l-4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ko7vgklqj {
  d: path("m4 20 4 -4h6l-4 4Z");
}

.mr1uq9olq {
  fill: currentColor;
  d: path("m4 20 4 -4h6l-4 4Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.rki_rg93o {
  d: path("m12 12 4 -4h6l-4 4Z");
}

.uudyrgb2a {
  d: path("M2 21 21 2");
}

</style>
