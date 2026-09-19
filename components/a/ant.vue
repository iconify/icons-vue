<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="ppgtnb6pt"><path class="ejm7rrbzs"/><path class="ga8uf1mjh"/><path class="v7158ub3m"/><ellipse class="biopk8-5b"/></g><path class="g00mydq5m"/><path class="yq87v89mh"/><path class="x1dbd3bkk"/><path class="m0wx9rbhj"/><g class="rv-emf-ct"><path class="rwyy1yvew"/><ellipse class="vbg6xw7ab"/></g><circle class="bkcmhjbrd"/><circle class="cjmxajetg"/><ellipse class="vxbs8cbop"/><circle class="li067ggmk"/><path class="pl3ounb7b"/><path class="gebvbtbek"/><path class="m8lfqtb8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:ant" /></template>
<style>
.biopk8-5b {
  cx: 22.6px;
  cy: 37.2px;
  rx: 8.5px;
  ry: 8.3px;
}

.bkcmhjbrd {
  cx: 24.4px;
  cy: 20.9px;
  r: 5.7px;
  fill: var(--svg-color--fcfcfa, #fcfcfa);
}

.cjmxajetg {
  cx: 24.4px;
  cy: 20.9px;
  r: 3.9px;
  fill: var(--svg-color--3e4347, #3e4347);
}

.ejm7rrbzs {
  d: path("M38.5 32.8c9.4-3.3 21.7 2.7 21.7 2.7s-5.4 12.3-14.8 15.6s-17.3 1.5-19.2-3.5c-2-5 2.9-11.4 12.3-14.8");
}

.g00mydq5m {
  fill: var(--svg-color--6c767a, #6c767a);
  d: path("M43.6 43.3s4 4.5 14.6 1.2c2.5-.8-7.6 13.1-9.2 15.6c2-2.1 16.8-15.2 12-18.7c-3.1-2.2-11.5.1-12.5-1.2z");
}

.ga8uf1mjh {
  d: path("M40.4 40c-1.1.4-7.6 3.1-9.3 4.5c-5.2 4 .5 14 1 16.1c-.1-2.2-1.4-11.5-.1-12.8c1.9-2 10.5-4.1 10.5-4.1zm-19.1.4c-.7.4-4.6 2.8-5.5 3.8c-2.5 2.9 5.5 6.8 6.7 7.7c-.9-1-5.3-5.3-4.8-6.2c.7-1.3 6.5-3.8 6.5-3.8z");
}

.gebvbtbek {
  fill: var(--svg-color--6c767a, #6c767a);
  d: path("M29.8 35.7c1-.7 7.1-5.3 8.5-7.1c4.4-5.6-4.8-14.4-5.9-16.4c.7 2.2 4.2 10.7 3 12.5c-4.1 5.8-9.3 8.1-9.3 8.1z");
}

.li067ggmk {
  cx: 8.5px;
  cy: 20.9px;
  r: 5.7px;
  fill: var(--svg-color--fcfcfa, #fcfcfa);
}

.m0wx9rbhj {
  fill: var(--svg-color--555c60, #555c60);
  d: path("M36.4 45s5.4 3.1 14.1 1c2.5-.6-6.6 13.5-8.2 16c2-2.1 15.6-14.7 10.7-18.3c-3.1-2.2-10.6-.9-11.6-2.1zM15.6 13.9c-1.7-2-3-4.2-4.6-6.1Q9.8 6.3 8.3 5.4c-1-.6-2-.9-2.9-.7c-.7.1-1.4-.4-1.5-1.2S4.2 2.1 5 2h.3c1.7 0 3.2.8 4.3 1.8s1.8 2.1 2.5 3.2c1.3 2.3 2.2 4.7 3.5 6.9m1.8 0c1.3-2.2 2.1-4.6 3.5-6.9c.7-1.1 1.4-2.3 2.5-3.2c1.1-1 2.6-1.7 4.3-1.8h.1c.8 0 1.4.6 1.4 1.3s-.6 1.3-1.3 1.4h-.3c-.9-.1-1.9.1-2.9.7s-1.8 1.5-2.6 2.4c-1.8 1.9-3.1 4.1-4.7 6.1");
}

.m8lfqtb8g {
  fill: var(--svg-color--555c60, #555c60);
  d: path("M29.7 36.1c1-.7 6.2-5.3 7.6-7.2c4.4-5.6-3.8-14.7-4.9-16.7c.7 2.2 4.1 11.7 3.1 13.5c-1.5 2.6-9.8 7-9.8 7z");
}

.pl3ounb7b {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M12.4 20.9c0 2.2-1.7 3.9-3.9 3.9c-2.1 0-3.9-1.8-3.9-3.9c0-2.2 1.7-3.9 3.9-3.9s3.9 1.8 3.9 3.9");
}

.ppgtnb6pt {
  fill: var(--svg-color--555c60, #555c60);
}

.rv-emf-ct {
  fill: var(--svg-color--6c767a, #6c767a);
}

.rwyy1yvew {
  d: path("M16.5 8.6c-7.1 0-12.8 5.6-12.8 12.5c0 8.2 12.9 16.7 12.8 16.7c0 0 12.8-8.5 12.8-16.7c0-6.9-5.8-12.5-12.8-12.5");
}

.v7158ub3m {
  d: path("M47.2 38.1c-1.1.4-7.6 3.1-9.3 4.5c-5.2 4 .5 14 1 16.1c-.1-2.1-1.5-11.4-.1-12.8c1.9-2 10.5-4.1 10.5-4.1z");
}

.vbg6xw7ab {
  cx: 24.4px;
  cy: 20.9px;
  rx: 6.5px;
  ry: 6.4px;
}

.vxbs8cbop {
  cx: 8.5px;
  cy: 20.9px;
  fill: var(--svg-color--6c767a, #6c767a);
  rx: 6.5px;
  ry: 6.4px;
}

.x1dbd3bkk {
  fill: var(--svg-color--6c767a, #6c767a);
  d: path("M36.9 45.3s4 4.5 14.6 1.2c2.5-.8-7.6 13.1-9.2 15.6c2-2.1 16.8-15.2 12-18.7c-3.1-2.2-11.5.1-12.5-1.2z");
}

.yq87v89mh {
  fill: var(--svg-color--555c60, #555c60);
  d: path("M43.2 43s5.4 3.1 14.1 1c2.5-.6-6.6 13.5-8.2 16c2-2.1 15.6-14.7 10.7-18.3c-3.1-2.2-10.6-.9-11.6-2.1z");
}

</style>
