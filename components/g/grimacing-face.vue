<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tg31urbgg"/><ellipse class="hg8187bsc"/><ellipse class="q-4sqnh6r"/><path class="ybfed9q5v"/><path class="yhbvxnbwk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:grimacing-face" /></template>
<style>
.hg8187bsc {
  cx: 12px;
  cy: 13.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.q-4sqnh6r {
  cx: 24px;
  cy: 13.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.tg31urbgg {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18c-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18");
}

.ybfed9q5v {
  fill: var(--svg-color--fff, #fff);
  d: path("M25 21a4 4 0 0 1 0 8H11a4 4 0 0 1 0-8z");
}

.yhbvxnbwk {
  fill: var(--svg-color--664500, #664500);
  d: path("M25 20H11c-2.757 0-5 2.243-5 5s2.243 5 5 5h14c2.757 0 5-2.243 5-5s-2.243-5-5-5m0 2a3 3 0 0 1 2.949 2.5H24.5V22zm-1.5 0v2.5h-3V22zm-4 0v2.5h-3V22zm-4 0v2.5h-3V22zM11 22h.5v2.5H8.051A3 3 0 0 1 11 22m0 6a3 3 0 0 1-2.949-2.5H11.5V28zm1.5 0v-2.5h3V28zm4 0v-2.5h3V28zm4 0v-2.5h3V28zm4.5 0h-.5v-2.5h3.449A3 3 0 0 1 25 28");
}

</style>
