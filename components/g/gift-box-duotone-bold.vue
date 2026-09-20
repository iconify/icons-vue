<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="u1uhlqgcz"/><path class="xzbn7sr9p"/><path class="akurgx2bb"/><path class="pvgr1jg2z"/><path class="em8xf33qp"/><path class="rw6ho_bav"/><path class="l2bljsbmn"/><path class="s7xlnnb_i"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:gift-box-duotone-bold" /></template>
<style>
.akurgx2bb {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9v11");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.em8xf33qp {
  d: path("M4 9v11h16V9");
}

.l2bljsbmn {
  d: path("M12 9v11");
}

.pvgr1jg2z {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M12 9 8 5h4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.rw6ho_bav {
  d: path("M2 9h20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.s7xlnnb_i {
  d: path("M12 9 8 5h4");
}

.u1uhlqgcz {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 9v11h16V9");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xzbn7sr9p {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M2 9h20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
