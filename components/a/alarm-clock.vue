<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<ellipse class="xhskjvq7r"/><ellipse class="x7zkyhbwy"/><path class="y7oxfdcix"/><path class="qy3f6zbov"/><path class="a62jdbn5a"/><g class="hkmbfwrqi"><circle class="t-drezvyp"/><path class="is1evtubj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:alarm-clock" /></template>
<style>
.a62jdbn5a {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("m20.6 46.6l10.3-10.5l1.2 1.2l-10.3 10.4z");
}

.hkmbfwrqi {
  fill: var(--svg-color--428bc1, #428bc1);
}

.is1evtubj {
  d: path("M30.2 21.7h3.7v15h-3.7zm3.7 12.2h7.5v3.7h-7.5z");
}

.qy3f6zbov {
  fill: var(--svg-color--b0b8b8, #b0b8b8);
  d: path("M5.7 23.6L23.3 5.7C21.1 3.4 18 2 14.5 2C7.6 2 2 7.7 2 14.6c0 3.5 1.4 6.7 3.7 9M40.5 5.8l17.8 17.7c2.3-2.3 3.7-5.4 3.7-8.9C62 7.7 56.4 2 49.4 2c-3.5.1-6.6 1.5-8.9 3.8");
}

.t-drezvyp {
  cx: 32.1px;
  cy: 35.8px;
  r: 3.7px;
}

.x7zkyhbwy {
  cx: 32.1px;
  cy: 35.8px;
  fill: var(--svg-color--fff, #fff);
  rx: 19.6px;
  ry: 19.7px;
}

.xhskjvq7r {
  cx: 32.1px;
  cy: 35.8px;
  fill: var(--svg-color--428bc1, #428bc1);
  rx: 25.2px;
  ry: 25.3px;
}

.y7oxfdcix {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M11 48.3L8.8 62h1.9c1.2 0 1.6-1.4 2.4-3.1c1-2.2 3.4-7.9 3.4-7.9zm42.1 0L55.4 62h-1.9c-1.2 0-1.6-1.4-2.4-3.1c-1-2.2-3.4-7.9-3.4-7.9zM13.3 10.2l5.9 5.9l-3.1 3.2l-5.9-6zm37.6 0L45 16.1l3.1 3.2l5.9-6z");
}

</style>
