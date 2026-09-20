<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="zyr0_hpav"/><path class="laoowrbvq"/><path class="y4_6s7b5v"/><path class="upedmnbef"/><path class="ie9u6rbsu"/><path class="ws9v8zbhe"/><path class="jynnt7brt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:dean-list-duotone-regular" /></template>
<style>
.ie9u6rbsu {
  d: path("M11 12h6");
}

.jynnt7brt {
  d: path("m8 6 2 2 -2 2 -2 -2Z");
}

.laoowrbvq {
  fill: currentColor;
  d: path("m8 6 2 2 -2 2 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.upedmnbef {
  d: path("M11 8h6");
}

.ws9v8zbhe {
  d: path("M11 16h6");
}

.y4_6s7b5v {
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
}

.zyr0_hpav {
  fill: currentColor;
  d: path("M4 5a2 2 0 0 1 2 -2h12a2 2 0 0 1 2 2v14a2 2 0 0 1 -2 2H6a2 2 0 0 1 -2 -2Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
