<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="y93qarhow"/><path class="strt8mboj"/><path class="d8cg8bc8o"/><path class="qsb3g-bwo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:coffee-machine-outline-regular" /></template>
<style>
.d8cg8bc8o {
  d: path("M12 13v2.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.qsb3g-bwo {
  d: path("M8 16h8v3a4 4 0 0 1 -8 0Z");
}

.strt8mboj {
  d: path("M7 8h6");
}

.y93qarhow {
  d: path("M4 6a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v5a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

</style>
