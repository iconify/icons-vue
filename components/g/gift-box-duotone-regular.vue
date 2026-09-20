<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="nrj6p8qat"><path class="m_r-ktvqm"/><path class="v_dlw1bwz"/><path class="t0sk4kw0y"/><path class="jm07qqbvr"/><path class="em8xf33qp"/><path class="rw6ho_bav"/><path class="l2bljsbmn"/><path class="s7xlnnb_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gift-box-duotone-regular" /></template>
<style>
.em8xf33qp {
  d: path("M4 9v11h16V9");
}

.jm07qqbvr {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 9 8 5h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.l2bljsbmn {
  d: path("M12 9v11");
}

.m_r-ktvqm {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M4 9v11h16V9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.nrj6p8qat {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.rw6ho_bav {
  d: path("M2 9h20");
}

.s7xlnnb_i {
  d: path("M12 9 8 5h4");
}

.t0sk4kw0y {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M12 9v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.v_dlw1bwz {
  stroke-width: var(--svg-stroke-width--5px, 5px);
  d: path("M2 9h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
