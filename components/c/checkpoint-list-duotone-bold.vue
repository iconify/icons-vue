<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qn-h03e3f"/><path class="zwjzc3g_l"/><path class="dt__4kvmv"/><path class="c1k-4f3qo"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="o40l0bbgl"/><path class="a3fwgxb1c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:checkpoint-list-duotone-bold" /></template>
<style>
.a3fwgxb1c {
  d: path("M9 11.5h6");
}

.c1k-4f3qo {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 11.5h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.crv4i00bu {
  d: path("M4 3v18");
}

.dt__4kvmv {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M9 8.5h6");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lulmb9b1a {
  d: path("M4 4h16v12H4");
}

.o40l0bbgl {
  d: path("M9 8.5h6");
}

.qn-h03e3f {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 3v18");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.s0phu2bbs {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2-5px, 2.5px);
}

.zwjzc3g_l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
