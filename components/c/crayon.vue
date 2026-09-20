<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="snfjl9-al"/><path class="npdea9amm"/><path class="xv3al0g4k"/><ellipse transform="rotate(-45.001 24.237 105.11)" class="oj0kl042z"/><path class="e2xvmobtx"/><path class="ijchyvrtc"/><path class="bu-q-p7wn"/><ellipse transform="rotate(-45.001 6.6 122.746)" class="klxcqkn7q"/><defs><path id="SVGTJs1b8Pb" transform="rotate(-45.001 69.08 60.204)" class="urgokfwxi"/></defs><clipPath id="SVGRK2brbEN"><use href="#SVGTJs1b8Pb"/></clipPath><ellipse clip-path="url(#SVGRK2brbEN)" transform="rotate(-44.928 81.758 68.988)" class="p-gqh1l8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:crayon" /></template>
<style>
.bu-q-p7wn {
  fill: var(--svg-color--e5502e, #e5502e);
  d: path("m9.53 125.81l21.38-11.14l-16.25-16.26l-11.13 21.4z");
}

.e2xvmobtx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M20.18 88.33c2.34-2.34 8.99.51 14.85 6.36c5.86 5.86 8.52 12.32 6.18 14.66l6.88-6.88l-.29-.29c.93-2.93-1.32-8.64-6.43-13.76c-5.11-5.11-11.41-7.93-14.33-7.01zM91.6 16.91c2.3-2.3 8.8.32 14.66 6.18s8.71 12.51 6.36 14.85l6.88-6.88l-.29-.29c.93-2.93-1.89-8.64-7.01-13.76c-5.11-5.11-10.83-7.93-13.76-7.01z");
}

.ijchyvrtc {
  fill: var(--svg-color--e5502e, #e5502e);
  d: path("M30.6 114.99c-1.81 1.81-6.94-.25-11.47-4.78s-6.61-9.66-4.8-11.47s6.83.39 11.36 4.92c4.52 4.53 6.72 9.52 4.91 11.33");
}

.klxcqkn7q {
  cx: 6.6px;
  cy: 122.75px;
  fill: var(--svg-color--c63720, #c63720);
  rx: 1.79px;
  ry: 4.47px;
}

.npdea9amm {
  fill: var(--svg-color--c63720, #c63720);
  d: path("M125.52 25.26c-1.81 1.81-7.01-5.5-11.53-10.02s-11.49-9.17-9.68-10.98s10.56-2.23 16.97 4.19c5.5 5.5 6.05 15 4.24 16.81");
}

.oj0kl042z {
  cx: 24.24px;
  cy: 105.11px;
  fill: var(--svg-color--c63720, #c63720);
  rx: 6px;
  ry: 15px;
}

.p-gqh1l8l {
  cx: 81.76px;
  cy: 68.99px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  rx: 30.7px;
  ry: 7.15px;
}

.snfjl9-al {
  fill: var(--svg-color--e5502e, #e5502e);
  d: path("M34.846 115.713L13.824 94.691l90.87-90.87l21.022 21.023z");
}

.urgokfwxi {
  d: path("M4.58 45.2h129v30h-129z");
}

.xv3al0g4k {
  fill: var(--svg-color--e5502e, #e5502e);
  d: path("M125.52 25.26c-2.34 2.34-9.73-.11-15.58-5.97S101.96 6.6 104.3 4.26s8.99.45 14.85 6.31s8.71 12.35 6.37 14.69");
}

</style>
