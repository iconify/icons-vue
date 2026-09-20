<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="kwuuvwbzr"/><path class="aagfc7h2t"/><path class="ktg13ccnh"/><path class="wc8nfbfle"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lake" /></template>
<style>
.aagfc7h2t {
  fill: var(--svg-color--1f1f1f, #1f1f1f);
  d: path("M3 3h18v18H3z");
}

.ft5dv1b6b {
  fill: none;
}

.ktg13ccnh {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.465 15.214v1.606a4.82 4.82 0 1 0 0-9.642v1.607a3.2 3.2 0 0 1 3.214 3.214a3.2 3.2 0 0 1-3.214 3.214");
}

.kwuuvwbzr {
  fill: var(--svg-color--fff, #fff);
  d: path("M21 3H3v18h18z");
}

.wc8nfbfle {
  fill: var(--svg-color--bdbec0, #bdbec0);
  d: path("M13.286 12H11.68a4.83 4.83 0 0 0 4.822 4.821v-1.607A3.203 3.203 0 0 1 13.286 12");
}

</style>
