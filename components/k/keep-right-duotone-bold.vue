<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="gmtljk7jt"/><path class="myme2pb3l"/><path class="flz2zhftx"/><path class="bp3yu1oem"/><path class="d0n0p9bwt"/><path class="mz0o03tol"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:keep-right-duotone-bold" /></template>
<style>
.bp3yu1oem {
  d: path("M12 22v-9l7 -7");
}

.d0n0p9bwt {
  d: path("M19 10.5V6h-4.5");
}

.flz2zhftx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M10 11 5 6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gmtljk7jt {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 22v-9l7 -7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.myme2pb3l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M19 10.5V6h-4.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.mz0o03tol {
  d: path("M10 11 5 6");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
