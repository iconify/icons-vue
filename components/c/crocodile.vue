<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="wjvo5-bsy"/><path class="zxcjjfbab"/><path class="h569hybvk"/><g class="cuhc3pb1x"><ellipse class="ik15meb7t"/><ellipse class="eij0i4amc"/><ellipse class="wvm-84b1k"/><ellipse class="yza8oebfh"/><ellipse class="dukf4bb3r"/></g><path class="vb9stccuy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:crocodile" /></template>
<style>
.cuhc3pb1x {
  fill: var(--svg-color--77b255, #77b255);
}

.dukf4bb3r {
  cx: 25.5px;
  cy: 26px;
  rx: 1.5px;
  ry: 1px;
}

.eij0i4amc {
  cx: 23.5px;
  cy: 24px;
  rx: 1.5px;
  ry: 1px;
}

.h569hybvk {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M10 18.123a1.5 1.5 0 1 0 3 0c0-.829-.671 0-1.5 0s-1.5-.829-1.5 0");
}

.ik15meb7t {
  cx: 27.5px;
  cy: 24px;
  rx: 1.5px;
  ry: 1px;
}

.vb9stccuy {
  fill: var(--svg-color--fff, #fff);
  d: path("M6 22c-.389 0-1-1-1-1h2s-.611 1-1 1m-2 .469C3.611 22.469 3 21 3 21h2s-.611 1.469-1 1.469M2 23c-.389 0-1-2-1-2h2s-.611 2-1 2");
}

.wjvo5-bsy {
  fill: var(--svg-color--3e721d, #3e721d);
  d: path("M19 32c0 1-1.723 3-3.334 3S14 33.657 14 32s1.306-3 2.916-3C18.527 29 19 30.343 19 32m11 0c0 1-1.723 3-3.334 3S25 33.657 25 32s1.306-3 2.916-3C29.527 29 30 30.343 30 32");
}

.wvm-84b1k {
  cx: 19.5px;
  cy: 24px;
  rx: 1.5px;
  ry: 1px;
}

.yza8oebfh {
  cx: 21.5px;
  cy: 26px;
  rx: 1.5px;
  ry: 1px;
}

.zxcjjfbab {
  fill: var(--svg-color--5c913b, #5c913b);
  d: path("M36 25c0-6-3.172-9.171-6-12c-1-1-1.399.321-1 1c.508.862 3 8-2 8h-2c-5 0-6.172-1.172-9-4c-4.5-4.5-7 0-9 0c-6 0-7-1.812-7 2c0 3 3 4 6 4s3 1 5 4c1.071 1.606 2.836 3.211 5.023 4.155c.232 1.119 2.774 3.845 4.311 3.845C21.944 36 22 34.657 22 33h5c.034 0 .066-.01.101-.01c.291.005.587.01.899.01c0 1 1.723 3 3.334 3S33 34.657 33 33c0-.302-.057-.587-.137-.861C34.612 31.193 36 29.209 36 25");
}

</style>
