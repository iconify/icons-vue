<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tg31urbgg"/><ellipse class="vrd83_b4t"/><ellipse class="j_ykwbb4m"/><path class="bn-v8rbar"/><path class="aemi5cd-b"/><path class="a70ku80wk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:disappointed-but-relieved-face" /></template>
<style>
.a70ku80wk {
  fill: var(--svg-color--664500, #664500);
  d: path("M30 13c-5.554 0-7.802-4.367-7.895-4.553a1 1 0 0 1 1.787-.899C23.967 7.694 25.713 11 30 11a1 1 0 1 1 0 2M6 13a1 1 0 0 1 0-2c5.083 0 5.996-3.12 6.033-3.253c.145-.528.69-.848 1.219-.709s.851.673.718 1.205C13.921 8.437 12.704 13 6 13");
}

.aemi5cd-b {
  fill: var(--svg-color--5dadec, #5dadec);
  d: path("M10 30c0 2.762-2.238 5-5 5s-5-2.238-5-5s4-10 5-10s5 7.238 5 10");
}

.bn-v8rbar {
  fill: var(--svg-color--664500, #664500);
  d: path("M23.485 27.879C23.474 27.835 22.34 23.5 18 23.5s-5.474 4.335-5.485 4.379a.5.5 0 0 0 .232.544a.51.51 0 0 0 .596-.06c.009-.007 1.013-.863 4.657-.863c3.59 0 4.617.83 4.656.863a.5.5 0 0 0 .59.073a.5.5 0 0 0 .239-.557");
}

.j_ykwbb4m {
  cx: 24.5px;
  cy: 16.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

.tg31urbgg {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M36 18c0 9.941-8.059 18-18 18c-9.94 0-18-8.059-18-18C0 8.06 8.06 0 18 0c9.941 0 18 8.06 18 18");
}

.vrd83_b4t {
  cx: 11.5px;
  cy: 16.5px;
  fill: var(--svg-color--664500, #664500);
  rx: 2.5px;
  ry: 3.5px;
}

</style>
