<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="i_pe1sf7d"/><circle class="tug10hbsj"/><circle class="teenvebbu"/><circle class="zfi1ojv3g"/><path class="o2wepbvrj"/><circle class="hxuxkg7-l"/><path class="upr92obtl"/><path class="w73xdsbht"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bear-face" /></template>
<style>
.hxuxkg7-l {
  cx: 18px;
  cy: 30px;
  r: 4px;
  fill: var(--svg-color--dd2e44, #dd2e44);
}

.i_pe1sf7d {
  cx: 7px;
  cy: 6px;
  r: 6px;
  fill: var(--svg-color--c1694f, #c1694f);
}

.o2wepbvrj {
  fill: var(--svg-color--c1694f, #c1694f);
  d: path("M35 22S33.692 0 18 0S1 22 1 22c0 5.872 4.499 10.323 12.216 11.61a5.982 5.982 0 0 0 9.568 0C30.501 32.323 35 27.872 35 22");
}

.teenvebbu {
  cx: 7px;
  cy: 6px;
  r: 4px;
  fill: var(--svg-color--e6aaaa, #e6aaaa);
}

.tug10hbsj {
  cx: 29px;
  cy: 6px;
  r: 6px;
  fill: var(--svg-color--c1694f, #c1694f);
}

.upr92obtl {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M18 20S7 23.687 7 27a6 6 0 0 0 11 3.315A6 6 0 0 0 29 27c0-3.313-11-7-11-7");
}

.w73xdsbht {
  fill: var(--svg-color--272b2b, #272b2b);
  d: path("M11 17s0-2 2-2s2 2 2 2v2s0 2-2 2s-2-2-2-2zm10 0s0-2 2-2s2 2 2 2v2s0 2-2 2s-2-2-2-2zm-7.875 8c-1.624 1 3.25 4 4.875 4s6.499-3 4.874-4s-8.124-1-9.749 0");
}

.zfi1ojv3g {
  cx: 29px;
  cy: 6px;
  r: 4px;
  fill: var(--svg-color--e6aaaa, #e6aaaa);
}

</style>
