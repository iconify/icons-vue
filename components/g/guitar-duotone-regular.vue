<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="rg2jtgbsm"/><path class="j8133bcoj"/><path class="onpg7rbrb"/><path class="jqvj67jvf"/><path class="qgw5bw59f"/><path class="o2mxw0jtm"/><path class="i9lkiobzn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:guitar-duotone-regular" /></template>
<style>
.i9lkiobzn {
  d: path("M10 5V2h4v3Z");
}

.j8133bcoj {
  fill: currentColor;
  d: path("M10 16.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.jqvj67jvf {
  d: path("M12 21c-3.5 0 -6 -2 -6 -4.5 0 -3 2.5 -4 3 -5.5h6c0.5 1.5 3 2.5 3 5.5 0 2.5 -2.5 4.5 -6 4.5");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.o2mxw0jtm {
  d: path("M12 5v6");
}

.onpg7rbrb {
  fill: currentColor;
  d: path("M10 5V2h4v3Z");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

.qgw5bw59f {
  d: path("M10 16.5a2 2 0 1 0 4 0 2 2 0 1 0 -4 0");
}

.rg2jtgbsm {
  fill: currentColor;
  d: path("M12 21c-3.5 0 -6 -2 -6 -4.5 0 -3 2.5 -4 3 -5.5h6c0.5 1.5 3 2.5 3 5.5 0 2.5 -2.5 4.5 -6 4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
  stroke: none;
}

</style>
