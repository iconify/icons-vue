<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="odlchqg5v"/><path class="vhnbtvbtn"/><path class="h2-rujbru"/><path class="azrfjy1oo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:kitchen-bin-outline-regular" /></template>
<style>
.azrfjy1oo {
  d: path("M14 5v3");
}

.h2-rujbru {
  d: path("M10 5v3");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.odlchqg5v {
  d: path("M6 9c0.5 4 1 8 2 11h8c1 -3 1.5 -7 2 -11");
}

.vhnbtvbtn {
  d: path("M3 8h18");
}

</style>
