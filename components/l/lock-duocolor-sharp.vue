<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="ay0o1u2ti"/><path class="el_r1pbzl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:lock-duocolor-sharp" /></template>
<style>
.ay0o1u2ti {
  stroke-opacity: 0.4;
  d: path("M9 10V6a3 3 0 0 1 6 0v4");
}

.el_r1pbzl {
  d: path("M4 10h16v11H4Z");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

</style>
