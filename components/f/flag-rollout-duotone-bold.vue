<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="s0phu2bbs"><path class="qn-h03e3f"/><path class="zwjzc3g_l"/><path class="sk9etkb4u"/><path class="bn16a-b9r"/><path class="ln--q6bsf"/><path class="crv4i00bu"/><path class="lulmb9b1a"/><path class="kow2ilbqy"/><path class="zos4srk3e"/><path class="y40ry_bij"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconmind:flag-rollout-duotone-bold" /></template>
<style>
.bn16a-b9r {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M11 8v5");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.crv4i00bu {
  d: path("M4 3v18");
}

.kow2ilbqy {
  d: path("M8 10v3");
}

.ln--q6bsf {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M14 6v7");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.lulmb9b1a {
  d: path("M4 4h16v12H4");
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

.sk9etkb4u {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M8 10v3");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.y40ry_bij {
  d: path("M14 6v7");
}

.zos4srk3e {
  d: path("M11 8v5");
}

.zwjzc3g_l {
  stroke-width: var(--svg-stroke-width--5-5px, 5.5px);
  d: path("M4 4h16v12H4");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
