<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x1ard9bpc"/><circle class="u1innptsz"/><circle class="pbgx89ygo"/><circle class="idi-am9bs"/><circle class="ahs8dwbsz"/><circle class="l19e1ibxc"/><circle class="iv9vvfb2d"/><circle class="y0ggqt1_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:grapes" /></template>
<style>
.ahs8dwbsz {
  cx: 27px;
  cy: 18px;
  r: 7px;
  fill: var(--svg-color--744eaa, #744eaa);
}

.idi-am9bs {
  cx: 19px;
  cy: 12px;
  r: 7px;
  fill: var(--svg-color--aa8dd8, #aa8dd8);
}

.iv9vvfb2d {
  cx: 18px;
  cy: 21px;
  r: 7px;
  fill: var(--svg-color--9266cc, #9266cc);
}

.l19e1ibxc {
  cx: 9px;
  cy: 26px;
  r: 7px;
  fill: var(--svg-color--744eaa, #744eaa);
}

.pbgx89ygo {
  cx: 10px;
  cy: 15px;
  r: 7px;
  fill: var(--svg-color--9266cc, #9266cc);
}

.u1innptsz {
  cx: 19px;
  cy: 29px;
  r: 7px;
  fill: var(--svg-color--553788, #553788);
}

.x1ard9bpc {
  fill: var(--svg-color--77b255, #77b255);
  d: path("M9.999 12a1 1 0 0 1-.446-.106c-4.38-2.19-7.484-7.526-8.501-10.578A.999.999 0 1 1 2.949.683c.877 2.632 3.688 7.517 7.499 9.422A1 1 0 0 1 9.999 12");
}

.y0ggqt1_b {
  cx: 29px;
  cy: 29px;
  r: 7px;
  fill: var(--svg-color--9266cc, #9266cc);
}

</style>
