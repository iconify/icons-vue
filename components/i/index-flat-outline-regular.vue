<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y-vga5bbj"/><path class="uilxv67me"/><path class="isrkj8blm"/><path class="bvj__8b4y"/><path class="rrc90qj9p"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:index-flat-outline-regular" /></template>
<style>
.bvj__8b4y {
  d: path("M20 4v11");
}

.isrkj8blm {
  d: path("M3 17h13");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rrc90qj9p {
  d: path("m18 13 2 2 2 -2");
}

.uilxv67me {
  d: path("M3 11h13");
}

.y-vga5bbj {
  d: path("M3 5h13");
}

</style>
