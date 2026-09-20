<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="o4tqyhbip"/><path class="jd882cb_k"/><path class="j33qrnb7r"/><path class="nq0_nyzpb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:iron-duotone-regular" /></template>
<style>
.j33qrnb7r {
  d: path("M10 11c0 -6 7 -6 7 0");
}

.jd882cb_k {
  d: path("m4 16 5 -5h9v5Z");
}

.nq0_nyzpb {
  d: path("M4 19h14");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o4tqyhbip {
  fill: currentColor;
  d: path("m4 16 5 -5h9v5Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
