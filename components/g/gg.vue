<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="oa3xnfbkh"/><path fill="url(#SVGshIH3bLw)" class="i8ckexi3q"/><path fill="url(#SVG79a9t8Zj)" class="b5mgllhxq"/><path class="t2u5d1fdo"/><path fill="url(#SVGl5YsEcTZ)" class="bi0veoiqg"/><defs><linearGradient id="SVGshIH3bLw" x1="12" x2="12" y1="5.5" y2="18.5" gradientUnits="userSpaceOnUse"><stop class="ya1cer-kb"/><stop offset=".36" class="g97rqb4yo"/><stop offset=".65" class="tr4f5vbks"/><stop offset="1" class="r5d2ox8us"/></linearGradient><linearGradient id="SVG79a9t8Zj" x1="12" x2="12" y1="5.5" y2="18.5" gradientUnits="userSpaceOnUse"><stop offset=".06" class="s796_bcvb"/><stop offset=".39" class="hqpb802-y"/><stop offset="1" class="jpsysbbun"/></linearGradient><linearGradient id="SVGl5YsEcTZ" x1="12" x2="12" y1="5.5" y2="12.2" gradientUnits="userSpaceOnUse"><stop class="l366kmcri"/><stop offset=".38" class="qt8tvuowz"/><stop offset=".93" class="aqwnttmfq"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gg" /></template>
<style>
.aqwnttmfq {
  stop-color: var(--svg-color--fca143, #fca143);
}

.b5mgllhxq {
  d: path("M12 15.06L6 18.5v-6.3l6-3.38z");
}

.bi0veoiqg {
  d: path("m6 12.2l-3-1.61l8.98-5.09L21 10.59l-3 1.61l-6.005-3.35z");
}

.ft5dv1b6b {
  fill: none;
}

.g97rqb4yo {
  stop-color: var(--svg-color--e26891, #e26891);
}

.hqpb802-y {
  stop-color: var(--svg-color--ea6d75, #ea6d75);
}

.i8ckexi3q {
  d: path("M21 16.875V10.6l-3 1.56v6.325z");
}

.jpsysbbun {
  stop-color: var(--svg-color--b961dc, #b961dc);
}

.l366kmcri {
  stop-color: var(--svg-color--eec985, #eec985);
}

.oa3xnfbkh {
  fill: var(--svg-color--5f2596, #5f2596);
  d: path("M3 16.875V10.6l3 1.56v6.325z");
}

.qt8tvuowz {
  stop-color: var(--svg-color--fdbd4d, #fdbd4d);
}

.r5d2ox8us {
  stop-color: var(--svg-color--b071d9, #b071d9);
}

.s796_bcvb {
  stop-color: var(--svg-color--ef7c3b, #ef7c3b);
}

.t2u5d1fdo {
  fill: var(--svg-color--5e2693, #5e2693);
  d: path("m12 15.06l6 3.44v-6.3l-6-3.38z");
}

.tr4f5vbks {
  stop-color: var(--svg-color--d45ac7, #d45ac7);
}

.ya1cer-kb {
  stop-color: var(--svg-color--f17750, #f17750);
}

</style>
