<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="pvuhr2fye"/><ellipse class="gre9x4bgp"/><path class="uuj53tbjw"/><path class="fq3hjsbws"/><circle class="wkio48bzz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:litter-in-bin-sign" /></template>
<style>
.fq3hjsbws {
  fill: var(--svg-color--fff, #fff);
  d: path("M6 22s-1 0-1-1s1-1 1-1s2 0 2 2v8h6v-8c0-2 2-2 2-2s1 0 1 1s-1 1-1 1v8s0 2-2 2H8s-2 0-2-2z");
}

.gre9x4bgp {
  cx: 23px;
  cy: 7.5px;
  fill: var(--svg-color--fff, #fff);
  rx: 3px;
  ry: 3.5px;
}

.pvuhr2fye {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M0 4c0-4 4-4 4-4h28s4 0 4 4v28s0 4-4 4H4s-4 0-4-4z");
}

.uuj53tbjw {
  fill: var(--svg-color--fff, #fff);
  d: path("M29 13s0-2-2-2h-7c-1 0-2 1-2 1l-2 2h-4s-1 0-1 1s1 1 1 1h5l2-2v17s0 1 1 1h1s1 0 1-1v-8s0-1 1-1s1 1 1 1v8s0 1 1 1h1s1 0 1-1v-9s2 0 2-2z");
}

.wkio48bzz {
  cx: 11px;
  cy: 20px;
  r: 2px;
  fill: var(--svg-color--fff, #fff);
}

</style>
