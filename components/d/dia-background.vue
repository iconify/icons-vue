<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGoG16EdSH)" class="r4i437pya"/><path class="jt1xju25c"/><path class="bm30oxzxe"/><path class="ax86sk02f"/></g><defs><linearGradient id="SVGoG16EdSH" x1="12" x2="12" y1="4" y2="20" gradientUnits="userSpaceOnUse"><stop class="x383f_b4p"/><stop offset=".292" class="ihf50ob9h"/><stop offset=".615" class="p8896nbus"/><stop offset=".857" class="cq41-obcz"/><stop offset="1" class="mpbzgebse"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dia-background" /></template>
<style>
.ax86sk02f {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.7 4L6.347 5.647v12.941h2.118c3.263 0 6.823-2.588 6.353-6.118c-.941 3.295-4.314 3.765-6.118 3.765z");
}

.bm30oxzxe {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.054 16.235H8.701V4h2.118c3.263 0 7.059 2.824 6.823 8.941c-.47-4.235-4.784-6.117-6.588-6.117z");
}

.cq41-obcz {
  stop-color: var(--svg-color--aebade, #aebade);
}

.ft5dv1b6b {
  fill: none;
}

.ihf50ob9h {
  stop-color: var(--svg-color--614397, #614397);
}

.jt1xju25c {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.053 8.706V6.823h2.353l3.53 2.824l.705 2.823c0 5.648-5.647 7.53-7.764 7.53s-3.53-1.177-3.53-1.412l3.53-.47c1.568-1.02 4.753-3.577 4.94-5.647c0-2.118-2.43-3.373-3.764-3.765");
}

.mpbzgebse {
  stop-color: var(--svg-color--c2dcf1, #c2dcf1);
}

.p8896nbus {
  stop-color: var(--svg-color--8071b3, #8071b3);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.x383f_b4p {
  stop-color: var(--svg-color--5a3b90, #5a3b90);
}

</style>
