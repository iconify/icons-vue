<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="q1m2erv2p"/><path class="luzp_sbwt"/><path class="nac320slo"/><ellipse class="hg8187bsc"/><ellipse class="q-4sqnh6r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:grinning-face" /></template>
<style>
.hg8187bsc {
  cx: 12px;
  cy: 13.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.luzp_sbwt {
  fill: var(--svg-color--664500, #664500);
  d: path("M18 21c-3.623 0-6.027-.422-9-1c-.679-.131-2 0-2 2c0 4 4.595 9 11 9c6.404 0 11-5 11-9c0-2-1.321-2.132-2-2c-2.973.578-5.377 1-9 1");
}

.nac320slo {
  fill: var(--svg-color--fff, #fff);
  d: path("M9 22s3 1 9 1s9-1 9-1s-2 4-9 4s-9-4-9-4");
}

.q-4sqnh6r {
  cx: 24px;
  cy: 13.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.q1m2erv2p {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--ffcc4d, #ffcc4d);
}

</style>
