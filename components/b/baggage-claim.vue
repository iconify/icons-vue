<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="ue_lvonqj"/><path class="zprkm9w8q"/><path class="zw2dazbre"/><g class="i2v6ey-hu"><ellipse class="n4ai2ac1p"/><circle class="i0f6pubvi"/><circle class="iarfpeqqu"/><circle class="k1s9qdbxt"/><ellipse class="h12bhhmyq"/><path class="hi3mwg-eh"/><circle class="g5nkl65oi"/><circle class="mo5qlg3gq"/><circle class="cf86rbcer"/><path class="a_gfzccbp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:baggage-claim" /></template>
<style>
.a_gfzccbp {
  d: path("M127.75 117.05a4.106 4.106 0 0 1-8.21 0a4.1 4.1 0 0 1 4.1-4.1c2.27 0 4.11 1.84 4.11 4.1");
}

.cf86rbcer {
  cx: 111.72px;
  cy: 117.05px;
  r: 4.1px;
}

.g5nkl65oi {
  cx: 87.86px;
  cy: 117.05px;
  r: 4.1px;
}

.h12bhhmyq {
  cx: 52.07px;
  cy: 117.05px;
  rx: 4.11px;
  ry: 4.1px;
}

.hi3mwg-eh {
  d: path("M68.11 117.05a4.106 4.106 0 0 1-8.21 0c0-2.27 1.83-4.1 4.11-4.1c2.26 0 4.1 1.84 4.1 4.1m11.93 0a4.106 4.106 0 0 1-8.21 0c0-2.27 1.83-4.1 4.11-4.1c2.26 0 4.1 1.84 4.1 4.1");
}

.i0f6pubvi {
  cx: 16.29px;
  cy: 117.05px;
  r: 4.1px;
}

.i2v6ey-hu {
  fill: var(--svg-color--ed6c30, #ed6c30);
}

.iarfpeqqu {
  cx: 28.22px;
  cy: 117.05px;
  r: 4.1px;
}

.k1s9qdbxt {
  cx: 40.15px;
  cy: 117.05px;
  r: 4.1px;
}

.mo5qlg3gq {
  cx: 99.79px;
  cy: 117.05px;
  r: 4.1px;
}

.n4ai2ac1p {
  cx: 4.36px;
  cy: 117.05px;
  rx: 4.11px;
  ry: 4.1px;
}

.ue_lvonqj {
  fill: var(--svg-color--ed6c30, #ed6c30);
  d: path("M119.07 92.37c0 6.76-5.53 12.29-12.29 12.29H21.22c-6.75 0-12.29-5.53-12.29-12.29V41.66c0-6.76 5.54-12.29 12.29-12.29h85.56c6.76 0 12.29 5.53 12.29 12.29z");
}

.zprkm9w8q {
  fill: var(--svg-color--ed6c30, #ed6c30);
  d: path("M79.58 49.66H48.43c-2.99 0-5.42-2.43-5.42-5.42V18.67c0-2.99 2.43-5.42 5.42-5.42h31.15c2.99 0 5.42 2.43 5.42 5.42v25.56c0 3-2.43 5.43-5.42 5.43M53.85 38.82h20.3V24.09h-20.3z");
}

.zw2dazbre {
  fill: var(--svg-color--fff, #fff);
  d: path("M25.34 29.36h9.01v75.29h-9.01zm68.32 0h9.02v75.29h-9.02z");
}

</style>
