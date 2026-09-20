<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<g class="t08tpdqjv"><circle class="hg4gp1bzv"/><circle class="k0rq6xfkq"/><circle class="dpcg4nbmf"/></g><g class="xbc8d1k8m"><circle class="yz8-v2soe"/><circle class="drbp_xb5g"/><circle class="c-v3ysr3z"/></g><path class="ylcpxngbd"/><path class="zbjqz9brb"/><path class="l7qxycrws"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:bubbles" /></template>
<style>
.c-v3ysr3z {
  cx: 29px;
  cy: 18px;
  r: 6px;
}

.dpcg4nbmf {
  cx: 10.5px;
  cy: 11.5px;
  r: 10.5px;
}

.drbp_xb5g {
  cx: 18px;
  cy: 29px;
  r: 5px;
}

.hg4gp1bzv {
  cx: 18px;
  cy: 29px;
  r: 6px;
}

.k0rq6xfkq {
  cx: 29px;
  cy: 18px;
  r: 7px;
}

.l7qxycrws {
  fill: var(--svg-color--fff, #fff);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M10.5 1c.68 0 1.344.07 1.988.195A5.5 5.5 0 0 1 13 3.5A5.5 5.5 0 0 1 2.227 5.057C4.15 2.593 7.14 1 10.5 1m12.579 13.283A4.494 4.494 0 0 0 32 13.5a4.45 4.45 0 0 0-.506-2.033A7 7 0 0 0 29 11a7 7 0 0 0-5.921 3.283M13.061 25.601A3.99 3.99 0 0 0 17 29a4 4 0 0 0 4-4c0-.466-.095-.907-.242-1.323A5.96 5.96 0 0 0 18 23a6 6 0 0 0-4.939 2.601");
}

.t08tpdqjv {
  fill: var(--svg-color--50a5e6, #50a5e6);
}

.xbc8d1k8m {
  fill: var(--svg-color--a8e0f9, #a8e0f9);
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
}

.ylcpxngbd {
  fill: var(--svg-color--f2f9ff, #f2f9ff);
  d: path("M10.5 19.5a1 1 0 0 1 0-2c3.309 0 6-2.691 6-6a1 1 0 0 1 2 0c0 4.411-3.589 8-8 8m23.5-1a1 1 0 0 0-2 0c0 1.378-1.122 2.5-2.5 2.5a1 1 0 0 0 0 2c2.481 0 4.5-2.019 4.5-4.5m-12 11a1 1 0 0 0-2 0c0 .827-.673 1.5-1.5 1.5a1 1 0 0 0 0 2c1.93 0 3.5-1.57 3.5-3.5");
}

.yz8-v2soe {
  cx: 10.5px;
  cy: 11.5px;
  r: 9.5px;
}

.zbjqz9brb {
  fill: var(--svg-color--fff, #fff);
  d: path("M3.5 13A1.5 1.5 0 0 1 2 11.5C2 6.813 5.813 3 10.5 3a1.5 1.5 0 1 1 0 3A5.506 5.506 0 0 0 5 11.5A1.5 1.5 0 0 1 3.5 13M27 18c0-1.103.897-2 2-2a1.5 1.5 0 1 0 0-3c-2.757 0-5 2.243-5 5a1.5 1.5 0 1 0 3 0M17 29c0-.551.449-1 1-1a1.5 1.5 0 1 0 0-3c-2.206 0-4 1.794-4 4a1.5 1.5 0 1 0 3 0");
}

</style>
