<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="k6sl9b-sa"/><path class="g4g7k28cx"/><path class="x96t6rbpf"/><path class="nhv6z5bmg"/><path class="o_lgmdh9h"/><path class="atoje4bsc"/><path class="njj_4bcir"/><path class="xj193cz1p"/><path class="e948j-b5x"/><path class="pmuiqo95v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:balcony-duotone-bold" /></template>
<style>
.atoje4bsc {
  d: path("M2 6h20");
}

.e948j-b5x {
  d: path("M18 6v11");
}

.g4g7k28cx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M6 6v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k6sl9b-sa {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 6h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nhv6z5bmg {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M18 6v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.njj_4bcir {
  d: path("M6 6v11");
}

.o_lgmdh9h {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 17h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pmuiqo95v {
  d: path("M2 17h20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.x96t6rbpf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 6v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xj193cz1p {
  d: path("M12 6v11");
}

</style>
