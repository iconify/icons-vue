<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="b6e35tlvq"/><path class="gzq8esb7v"/><path class="ey6vz5bjx"/><path class="g5i0djbdl"/><path class="obdvbgbhd"/><path class="r7xk8o29f"/><path class="k4qo1xe9v"/><path class="bai-ikdbm"/><path class="qorafhbcl"/><path class="qw7b_6b1t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:fair-trade-duotone-bold" /></template>
<style>
.b6e35tlvq {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 4v16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.bai-ikdbm {
  d: path("M9 6a3 3 0 0 1 -6 0");
}

.ey6vz5bjx {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 6a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.g5i0djbdl {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M21 6a3 3 0 0 1 -6 0");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.gzq8esb7v {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 6h16");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.k4qo1xe9v {
  d: path("M4 6h16");
}

.obdvbgbhd {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 20h8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.qorafhbcl {
  d: path("M21 6a3 3 0 0 1 -6 0");
}

.qw7b_6b1t {
  d: path("M8 20h8");
}

.r7xk8o29f {
  d: path("M12 4v16");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

</style>
