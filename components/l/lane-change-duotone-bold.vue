<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="p4o40ib9j"/><path class="zi-05bc7q"/><path class="fdx5lo1-l"/><path class="u0u_7p8ua"/><path class="lwdt7zb5f"/><path class="pk1ekjvnl"/><path class="xtovmhbxk"/><path class="codat6b9f"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:lane-change-duotone-bold" /></template>
<style>
.codat6b9f {
  d: path("M11.5 6H15v3.5");
}

.fdx5lo1-l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 19v-7l6 -6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lwdt7zb5f {
  d: path("M4 2v20");
}

.p4o40ib9j {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.pk1ekjvnl {
  d: path("M20 2v20");
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.u0u_7p8ua {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11.5 6H15v3.5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.xtovmhbxk {
  d: path("M9 19v-7l6 -6");
}

.zi-05bc7q {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M20 2v20");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
