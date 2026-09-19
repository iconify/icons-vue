<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="l28lv0bir"/><path class="lfpx0mzka"/><path class="l4kg_ebxu"/><path class="dst0d147f"/><g class="wc59uxbku"><circle class="olgd34b3l"/><circle class="rw__5_bht"/><path class="q1roacbnr"/></g><path class="blzer9akc"/><path class="wipp2qj3t"/><g class="wc59uxbku"><circle class="c98q0_bdm"/><circle class="lcitnzblp"/><path class="bxky4dbtp"/></g><path class="isippzf9f"/><path class="dxdr6vzki"/><path class="ed_va30td"/><g class="wc59uxbku"><circle class="zejpo0b4g"/><circle class="zhdo7z-ll"/><path class="jgdwwcbqt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:family" /></template>
<style>
.blzer9akc {
  fill: var(--svg-color--ffb300, #ffb300);
  d: path("m31.9 17.3l1.5 2.8h26.2l1.1-2.9c0-10.6-2.5-15-14.1-15.1c-11.8-.2-14.7 4.5-14.7 15.2");
}

.bxky4dbtp {
  d: path("M50.1 27.2c-2.3 1.8-4.9 1.8-7.2 0c-.3-.2-.5.2-.3.5c.7 1.3 2.1 2.4 3.9 2.4s3.2-1.1 3.9-2.4c.2-.4 0-.8-.3-.5");
}

.c98q0_bdm {
  cx: 41px;
  cy: 20.3px;
  r: 2.2px;
}

.dst0d147f {
  fill: var(--svg-color--ffdd67, #ffdd67);
  d: path("M6.4 23.6s-2.2-.6-2.2-3.9c0-2.6 1.7-3.1 1.7-3.1c6 0 15.8-7.8 15.8-7.8s3.7 6.9 7.3 7.8c0 0 1.7.3 1.7 3.1c0 3.3-2.3 3.9-2.3 3.9c0 5-6.8 10-11 10c-4 0-11-5-11-10");
}

.dxdr6vzki {
  fill: var(--svg-color--ffb300, #ffb300);
  d: path("M32 36c-6.7 0-10.9 3.8-10.9 8.5v3.2c0 3.7 2.9 3.7 2.9 3.7h16.4s2.5 0 2.5-3.7v-3.2c0-4.7-4.4-8.5-10.9-8.5");
}

.ed_va30td {
  fill: var(--svg-color--ffdd67, #ffdd67);
  d: path("m22.1 48.5l.4-4.5c0-2.9 4.5-.6 9.5-.6s9.5-2.3 9.5.6l.4 4.5c2.2 0 2.2 3.5 0 3.5c0 4.4-5.9 7-9.9 7s-9.9-2.6-9.9-7c-2.1 0-2.1-3.5 0-3.5");
}

.isippzf9f {
  fill: var(--svg-color--29b6f6, #29b6f6);
  d: path("M44.5 62h-25c0-8.4 25-8.4 25 0");
}

.jgdwwcbqt {
  d: path("M28.9 54.4c2 1.5 4.3 1.5 6.3 0c.2-.2.5.1.3.4c-.6 1.1-1.9 2-3.4 2c-1.6 0-2.8-1-3.4-2c-.3-.3-.1-.6.2-.4");
}

.l28lv0bir {
  fill: var(--svg-color--ffb300, #ffb300);
  d: path("M17 2C7.3 2 2 8.3 2 16.7v18.5h30V16.7c0-12.4-8.1-12.2-8.1-12.2S23.3 2 17 2");
}

.l4kg_ebxu {
  fill: var(--svg-color--c2185b, #c2185b);
  d: path("M2 34.8V62h30V34.8c0-5.8-30-5.8-30 0");
}

.lcitnzblp {
  cx: 52px;
  cy: 20.3px;
  r: 2.2px;
}

.lfpx0mzka {
  fill: var(--svg-color--01579b, #01579b);
  d: path("M32 34.8V62h30V34.8c0-5.8-30-5.8-30 0");
}

.olgd34b3l {
  cx: 12.1px;
  cy: 20.3px;
  r: 2.2px;
}

.q1roacbnr {
  d: path("M21.1 27.2c-2.3 1.8-4.9 1.8-7.2 0c-.3-.2-.5.2-.3.5c.7 1.3 2.1 2.4 3.9 2.4s3.2-1.1 3.9-2.4c.2-.4 0-.8-.3-.5");
}

.rw__5_bht {
  cx: 22.9px;
  cy: 20.3px;
  r: 2.2px;
}

.wc59uxbku {
  fill: var(--svg-color--937237, #937237);
}

.wipp2qj3t {
  fill: var(--svg-color--ffdd67, #ffdd67);
  d: path("M59.7 17.1c-.1.6-.2 1.2-.4 1.5c-.3.6-.9.9-.9.9s.2-1.2.1-2.8c-.7-9.7-1.2-5.1-11.9-5.1s-11.3-4.7-11.9 5c-.1 1.7.1 2.8.1 2.8s-.6-.3-.9-.9c-.2-.3-.3-.9-.4-1.5c-1-.3-2.3 0-2.3 2.9c0 1.8.7 3.3 2.9 3.5c.8 6.1 8.9 10.1 12.6 10.1c3.6 0 11.8-4.1 12.6-10.1c2.2-.2 2.9-1.7 2.9-3.5c-.2-2.8-1.5-3-2.5-2.8");
}

.zejpo0b4g {
  cx: 27.2px;
  cy: 49.8px;
  r: 1.8px;
}

.zhdo7z-ll {
  cx: 36.8px;
  cy: 49.8px;
  r: 1.8px;
}

</style>
