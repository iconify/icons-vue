<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="qlvopac9f"/><path class="u9sucr35v"/><path class="of4kqrbvd"/><path class="gqriggbpc"/><path class="agsz4bbea"/><path class="crv4i00bu"/><path class="wwb_9fbub"/><path class="je5qtm2zh"/><path class="g1xwr4cnp"/><path class="t2ilqxxwv"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:index-bloat-duotone-regular" /></template>
<style>
.agsz4bbea {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 18h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.crv4i00bu {
  d: path("M4 3v18");
}

.g1xwr4cnp {
  d: path("M4 14h15");
}

.gqriggbpc {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 14h15");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.je5qtm2zh {
  d: path("M4 10h17");
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.of4kqrbvd {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 10h17");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qlvopac9f {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.t2ilqxxwv {
  d: path("M4 18h8");
}

.u9sucr35v {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 6h12");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.wwb_9fbub {
  d: path("M4 6h12");
}

</style>
