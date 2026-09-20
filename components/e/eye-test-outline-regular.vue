<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y4_6s7b5v"/><path class="zvg3vyivl"/><path class="pt-3kkb2k"/><path class="v7ievg3-e"/><path class="ugvz7ebru"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:eye-test-outline-regular" /></template>
<style>
.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.pt-3kkb2k {
  d: path("M9 11h6");
}

.ugvz7ebru {
  d: path("M10 18h4");
}

.v7ievg3-e {
  d: path("M9.5 15h5");
}

.y4_6s7b5v {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.zvg3vyivl {
  d: path("M8 7h8");
}

</style>
