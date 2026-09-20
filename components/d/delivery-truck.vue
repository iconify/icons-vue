<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="b328mqb-c"/><path class="yxrnbmb-i"/><path class="tsvthtbzd"/><path class="a-1s8u67c"/><path class="i9ut8ac3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:delivery-truck" /></template>
<style>
.a-1s8u67c {
  fill: var(--svg-color--fff, #fff);
  d: path("M47.99 70.16c0 1.78-1.45 3.23-3.23 3.23H32.12c-1.78 0-3.02-1.44-2.77-3.19l2.23-15.4c.25-1.76 1.92-3.2 3.69-3.2h9.49c1.77 0 3.23 1.46 3.23 3.23z");
}

.b328mqb-c {
  fill: var(--svg-color--757f3f, #757f3f);
  d: path("M127.56 41.19c0-1.78-1.45-3.23-3.23-3.23H55.16c-1.77 0-3.23 1.45-3.23 3.23v50.58h75.63z");
}

.i9ut8ac3u {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M37.54 109.29c0 6.21-5.04 11.24-11.25 11.24s-11.25-5.03-11.25-11.24c0-6.22 5.04-11.24 11.25-11.24s11.25 5.02 11.25 11.24m67.76 0c0 6.21-5.04 11.24-11.25 11.24S82.8 115.5 82.8 109.29c0-6.22 5.04-11.24 11.25-11.24s11.25 5.02 11.25 11.24");
}

.tsvthtbzd {
  fill: var(--svg-color--78a3ad, #78a3ad);
  d: path("M51.93 91.77V45.72H34.39c-3.16 0-7.77 2.4-8.48 7.9c-1.05 8.08-3.45 20.15-3.45 20.15L6.6 79.71S.44 81.7.44 89.28v15.15c0 2.05 2.52 4.85 4.42 4.85h119.47c1.78 0 3.23-1.45 3.23-3.23V91.77z");
}

.yxrnbmb-i {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M75.27 40.96h3.42v47.45h-3.42zm24.86 0h3.42v47.45h-3.42z");
}

</style>
