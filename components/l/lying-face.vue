<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wkr7-fmmx"/><path class="j9of7jmlc"/><circle class="y38sttb6l"/><path class="l45n42b3q"/><g class="fbp0m0b1e"><circle class="cqml_ebfd"/><path class="eu7dn47li"/></g><path class="p5sr_yb-d"/><path class="n_-3l0baf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:lying-face" /></template>
<style>
.cqml_ebfd {
  cx: 40.7px;
  cy: 28.2px;
  r: 3.2px;
}

.eu7dn47li {
  d: path("M45.7 48c-1.4-3.6-4.8-6-12.7-6c-8 0-11.3 2.4-12.7 6c-.7 1.9.3 4 .3 4c.4 1.2 2.1 2 12.4 2s12-.8 12.4-2c0 0 1.1-2.1.3-4");
}

.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.j9of7jmlc {
  fill: var(--svg-color--fff, #fff);
  d: path("M30.4 26.1c0 5.4-4.3 9.7-9.7 9.7S11 31.5 11 26.1c0-5.3 4.3-9.7 9.7-9.7s9.7 4.3 9.7 9.7");
}

.l45n42b3q {
  fill: var(--svg-color--fff, #fff);
  d: path("M54.7 26.1c0 5.4-4.3 9.7-9.7 9.7s-9.7-4.3-9.7-9.7s4.3-9.7 9.7-9.7c5.3 0 9.7 4.3 9.7 9.7");
}

.n_-3l0baf {
  fill: var(--svg-color--eba352, #eba352);
  d: path("M30.6 39.3c-7.3 1.3-15.7 1.8-23.1 1.2c-8.7-.7-6.2-11.2 1-9.6c7.3 1.3 14.7 1.8 22.1 1.3c4.5-.2 4.6 6.1 0 7.1");
}

.p5sr_yb-d {
  fill: var(--svg-color--fff, #fff);
  d: path("M42 47.1c.1-.2 0-.5-.2-.7c0 0-2-1.9-8.8-1.9s-8.8 1.9-8.8 1.9c-.2.2-.2.5-.2.7l.2.5c.1.2.3.4.5.4h16.6c.2 0 .5-.2.5-.4z");
}

.wkr7-fmmx {
  fill: var(--svg-color--ffdd67, #ffdd67);
  d: path("M62 32c0 15.5-10 28-28 28C18.5 60 6 47.5 6 32S18.5 4 34 4s28 12.5 28 28");
}

.y38sttb6l {
  cx: 24px;
  cy: 28.2px;
  r: 3.2px;
  fill: var(--svg-color--664e27, #664e27);
}

</style>
