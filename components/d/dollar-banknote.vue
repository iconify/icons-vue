<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="uh0_vlbvo"/><path class="hjjsh_bav"/><path class="c3l22j6pw"/><path class="zbyz74b9n"/><path class="w0eevtqcy"/><circle class="qgs1dlynt"/><path class="g0169xokb"/><path class="y8flyabgq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:dollar-banknote" /></template>
<style>
.c3l22j6pw {
  fill: var(--svg-color--94989b, #94989b);
  d: path("M24 46.5h16v9H24z");
}

.g0169xokb {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("M24 8.5h16v38H24z");
}

.hjjsh_bav {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M0 8.5h64v38H0z");
}

.qgs1dlynt {
  cx: 45px;
  cy: 27.5px;
  r: 8px;
  fill: var(--svg-color--699635, #699635);
}

.uh0_vlbvo {
  fill: var(--svg-color--699635, #699635);
  d: path("M0 46.5h64v9H0z");
}

.w0eevtqcy {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M7 15.5h50v24H7z");
}

.y8flyabgq {
  fill: var(--svg-color--fff, #fff);
  d: path("M16 26.5c-1.1 0-2-.9-2-2s.9-2 2-2s2 .9 2 2h2c0-1.9-1.3-3.4-3-3.9v-1.1h-2v1.1c-1.7.4-3 2-3 3.9c0 2.2 1.8 4 4 4c1.1 0 2 .9 2 2s-.9 2-2 2s-2-.9-2-2h-2c0 1.9 1.3 3.4 3 3.9v1.1h2v-1.1c1.7-.4 3-2 3-3.9c0-2.2-1.8-4-4-4");
}

.zbyz74b9n {
  fill: var(--svg-color--699635, #699635);
  d: path("M4 12.5h56v30H4z");
}

</style>
