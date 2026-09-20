<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ux6apgnet"/><path class="u6ltz0bsa"/><path class="z5j-qdr3m"/><path class="hsrzt0bgt"/><path class="o5ex3bb1u"/><path class="lnxxf4b_g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fireworks-outline-regular" /></template>
<style>
.hsrzt0bgt {
  d: path("m10 8 3 -3");
}

.lnxxf4b_g {
  d: path("m19 19 2 2");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o5ex3bb1u {
  d: path("M16 17a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.u6ltz0bsa {
  d: path("M8 7V4");
}

.ux6apgnet {
  d: path("M7 10a1 1 0 1 0 2 0 1 1 0 1 0 -2 0");
}

.z5j-qdr3m {
  d: path("M6 8 3 5");
}

</style>
