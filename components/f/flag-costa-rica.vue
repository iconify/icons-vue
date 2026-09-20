<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="e8e7ydbal"/><path class="cheer6p9w"/><path class="h10qszx-f"/><ellipse class="ccwc6cpzv"/><path class="mdmxjac4a"/><ellipse class="j-qbpd-2j"/><ellipse class="a12wetbph"/><ellipse class="ec6izob-m"/><ellipse class="xqvnb-slm"/><path class="p_cjy5b5w"/><ellipse class="i1ikcxx9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-costa-rica" /></template>
<style>
.a12wetbph {
  cx: 8.5px;
  cy: 16px;
  fill: var(--svg-color--89c5e4, #89c5e4);
  rx: 1.5px;
  ry: 1px;
}

.ccwc6cpzv {
  cx: 8.5px;
  cy: 18px;
  fill: var(--svg-color--eee, #eee);
  rx: 3.5px;
  ry: 4px;
}

.cheer6p9w {
  fill: var(--svg-color--eee, #eee);
  d: path("M0 9h36v18H0z");
}

.e8e7ydbal {
  fill: var(--svg-color--002b7f, #002b7f);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

.ec6izob-m {
  cx: 8.5px;
  cy: 18.5px;
  fill: var(--svg-color--088930, #088930);
  rx: 1.5px;
  ry: 2.5px;
}

.h10qszx-f {
  fill: var(--svg-color--ce1225, #ce1225);
  d: path("M0 13h36v10H0z");
}

.i1ikcxx9u {
  cx: 8.5px;
  cy: 18.5px;
  fill: var(--svg-color--dca841, #dca841);
  rx: 1.5px;
  ry: 0.5px;
}

.j-qbpd-2j {
  cx: 8.5px;
  cy: 19.5px;
  fill: var(--svg-color--dca841, #dca841);
  rx: 2.5px;
  ry: 1.5px;
}

.mdmxjac4a {
  fill: var(--svg-color--f4cb58, #f4cb58);
  d: path("M10.269 19.5c0 .828-.792 2.079-1.769 2.079S6.731 20.328 6.731 19.5S7.523 18 8.5 18s1.769.671 1.769 1.5");
}

.p_cjy5b5w {
  fill: var(--svg-color--89c5e4, #89c5e4);
  d: path("M10 18c0 1.104-.671 2-1.5 2S7 19.104 7 18s.671-1.498 1.5-1.498S10 16.896 10 18");
}

.xqvnb-slm {
  cx: 8.5px;
  cy: 16.5px;
  fill: var(--svg-color--dca841, #dca841);
  rx: 1.5px;
  ry: 0.5px;
}

</style>
