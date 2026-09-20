<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="uclajbbyh"/><path class="oqwl7xbel"/><path class="ja2m7eb_d"/><circle class="g8p84__nj"/><circle class="txq1fgblm"/><circle class="o039geycu"/><circle class="v2136_n0u"/><path class="xur__9blv"/><path class="hnr4-kvjp"/><path class="opsrj2b0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:fire-engine" /></template>
<style>
.g8p84__nj {
  cx: 7px;
  cy: 31px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

.hnr4-kvjp {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M8 11a1 1 0 0 1-1 1H5a1 1 0 0 1 0-2h2a1 1 0 0 1 1 1");
}

.ja2m7eb_d {
  fill: var(--svg-color--f5f8fa, #f5f8fa);
  d: path("M2 22h32v3H2z");
}

.o039geycu {
  cx: 28px;
  cy: 31px;
  r: 4px;
  fill: var(--svg-color--292f33, #292f33);
}

.opsrj2b0n {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M10 11a1 1 0 0 1-1 1H7a1 1 0 0 1 0-2h2a1 1 0 0 1 1 1");
}

.oqwl7xbel {
  fill: var(--svg-color--dd2e44, #dd2e44);
  d: path("M32 14H14s.041-2-2.979-2H5.146C0 12 0 19.959 0 19.959V27a4 4 0 0 0 4 4h28a4 4 0 0 0 4-4v-9a4 4 0 0 0-4-4");
}

.txq1fgblm {
  cx: 7px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--8899a6, #8899a6);
}

.uclajbbyh {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M35 8H13a1 1 0 0 0 0 2h2v2h2v-2h2v2h2v-2h2v2h2v-2h2v2h2v-2h2v2h2v-2h2a1 1 0 1 0 0-2m1 5a1 1 0 0 1-1 1H13a1 1 0 0 1 0-2h22a1 1 0 0 1 1 1");
}

.v2136_n0u {
  cx: 28px;
  cy: 31px;
  r: 2px;
  fill: var(--svg-color--8899a6, #8899a6);
}

.xur__9blv {
  fill: var(--svg-color--55acee, #55acee);
  d: path("M7 20H2s0-6 3-6h2zm5 0H9v-6h1c1 0 2 1 2 2z");
}

</style>
