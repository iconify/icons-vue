<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="hcnug392v"/><path class="eg8fxcfrq"/><circle class="l3h4jubdy"/><circle class="v__yun_zc"/><circle class="wd3g6hzga"/><circle class="q361c4b4b"/><circle class="xaqw56b7b"/><circle class="qrl131b3o"/><path class="hgjam-k6c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:boy-medium-light-skin-tone" /></template>
<style>
.eg8fxcfrq {
  fill: var(--svg-color--fed0ac, #fed0ac);
  d: path("M57.2 33s-.8-3.3-1.2-10.2c-.5-7.5-10.9-1.5-24-1.5s-23.5-6-24 1.5C7.6 29.7 6.8 33 6.8 33c-6.5 0-6.5 10.6.4 10.6C7.2 55 21.5 62 32 62s24.8-7 24.8-18.4c6.9 0 6.9-10.6.4-10.6");
}

.hcnug392v {
  fill: var(--svg-color--dbb471, #dbb471);
  d: path("M32 2c23 0 28 15.3 28 24c0 7.7-1 11-1 11H5s-1-3.3-1-11C4 17.3 9 2 32 2");
}

.hgjam-k6c {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M40.1 48.1c-5.2 3.6-11 3.6-16.2 0c-.6-.4-1.2.3-.8 1c1.6 2.6 4.8 4.9 8.9 4.9s7.3-2.3 8.9-4.9c.4-.7-.2-1.4-.8-1");
}

.l3h4jubdy {
  cx: 44.5px;
  cy: 35.5px;
  r: 6.5px;
  fill: var(--svg-color--fff, #fff);
}

.q361c4b4b {
  cx: 19.5px;
  cy: 35.5px;
  r: 6.5px;
  fill: var(--svg-color--fff, #fff);
}

.qrl131b3o {
  cx: 19.5px;
  cy: 35.5px;
  r: 1.5px;
  fill: var(--svg-color--231f20, #231f20);
}

.v__yun_zc {
  cx: 44.5px;
  cy: 35.5px;
  r: 4.5px;
  fill: var(--svg-color--664e27, #664e27);
}

.wd3g6hzga {
  cx: 44.5px;
  cy: 35.5px;
  r: 1.5px;
  fill: var(--svg-color--231f20, #231f20);
}

.xaqw56b7b {
  cx: 19.5px;
  cy: 35.5px;
  r: 4.5px;
  fill: var(--svg-color--664e27, #664e27);
}

</style>
