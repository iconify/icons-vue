<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="vuzvxvzyw"/><path class="msw0kpbrx"/><path class="qpjx1_bgn"/><path class="xkheykrbh"/><path class="qd-hxvwib"/><path class="jv0w4_bji"/><g class="euxxm2bmm"><path class="yj4l7ybao"/><path class="vituau0yl"/></g><path class="rly9webev"/><ellipse class="dr85pmear"/><g class="jeunsn1yj"><ellipse transform="rotate(-10.003 23.562 42.312)" class="mvh9d3bub"/><ellipse transform="rotate(-79.997 40.438 42.31)" class="z10ug_d7e"/></g><g class="euxxm2bmm"><path class="xmxyh1b3k"/><path class="dy6b1-c-x"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:deer" /></template>
<style>
.dr85pmear {
  cx: 32px;
  cy: 55.4px;
  fill: var(--svg-color--fff, #fff);
  rx: 3.3px;
  ry: 0.9px;
}

.dy6b1-c-x {
  d: path("M28.3 28.7c-1.8 1.8-2.9 3.7-.6 8.3c2.6 5.2 1.7 14.7 4.3 14.7c2.7 0 1.8-9.5 4.3-14.7c2.3-4.6 1.2-6.5-.6-8.3c-1.3-.2-2.5-.2-3.7-.2s-2.4.1-3.7.2");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.euxxm2bmm {
  fill: var(--svg-color--89664c, #89664c);
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.jv0w4_bji {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("M36.5 35.7s0-15.3 14.5-15.3c.1 0 0 15.3-14.5 15.3");
}

.msw0kpbrx {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("M42.7 39.4c-2.5-4.5.5-7.3-1.4-8.6c-3.2-2.2-6.4-2.3-9.3-2.3s-6.1.1-9.3 2.3c-1.9 1.2 1.1 4.1-1.4 8.6s-.2 8.4 2.8 11.1c3 2.6.2 8.4 4.4 10.6c1 .5 2.2 1 3.5 1s2.5-.5 3.5-1c4.2-2.2 1.4-7.9 4.4-10.6c3.1-2.7 5.4-6.6 2.8-11.1");
}

.mvh9d3bub {
  cx: 23.6px;
  cy: 42.3px;
  rx: 1.7px;
  ry: 2.4px;
}

.qd-hxvwib {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M15.4 22.6s5.5 0 9.6 7.6c0 0-3.3-1.8-2.8-1s2.9 2.6.4 1.7c-2.4-.9-.8.7 0 1.5c.8.7-7.2-1.5-7.2-9.8");
}

.qpjx1_bgn {
  fill: var(--svg-color--89664c, #89664c);
  d: path("M41.7 35.9c.1 1 .3 2.2 1.1 3.5c2.5 4.5.2 8.4-2.8 11.1c-1.3 1.1-1.5 2.7-1.7 4.4c0-2.4.2-6.7 1.9-11.1c1.4-3.9 1.5-5.8 1.5-7.9m-19.4 0c-.1 1-.3 2.2-1.1 3.5c-2.5 4.5-.2 8.4 2.8 11.1c1.3 1.1 1.5 2.7 1.7 4.4c0-2.4-.2-6.7-1.9-11.1c-1.4-3.9-1.5-5.8-1.5-7.9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.rly9webev {
  fill: var(--svg-color--594640, #594640);
  d: path("M32 53.9c-2 0-4.5.3-4.5 1.4s1.8 3.6 4.5 3.6s4.5-2.5 4.5-3.6s-2.5-1.4-4.5-1.4");
}

.vituau0yl {
  d: path("M31.5 58.2h.9v1.9h-.9z");
}

.vuzvxvzyw {
  fill: var(--svg-color--594640, #594640);
  d: path("M21.9 21.9c-.6-1.6-1.1-3-1.4-4.2C30.6 12.3 27.4 7.3 25 11c-1.6 2.6-4 3.8-5 4.2c-.4-3.3.3-5.5.6-7.9c.6-3.9-3.1-5.8-3.6-4.3c-.8 2.3 2.5.9 1.5 6.4c-.8 4.2-.1 7.8.6 10c-1.5-1.2-3.1-2.4-4.9-3.6c-1.2-2.3-2.7-7 .7-12.2c1-1.6-.3-1.7-.8-1.6c-1.7.5-4.2 6.6-2.8 11.9C4.3 8.9 6.8 2 5.1 2c-2.1 0-1 7.7 2 11.5c1 1.2 2.9 2.6 5.1 4c-1.8.8-5.1 1.4-8.4-1.5c-.4-.2-1.8-.9-1.8.9s5.9 6.6 12.5 2.3c2.8 1.9 5.6 4 6.8 6.2l5.8 5.2c-.6-3.2-2.5-6-5.2-8.7m20.2 0c.7-1.6 1.1-3 1.4-4.2C33.4 12.3 36.6 7.3 39 11c1.6 2.6 4 3.8 5 4.2c.4-3.3-.3-5.5-.6-7.9c-.6-3.9 3.1-5.8 3.6-4.3c.8 2.3-2.5.9-1.5 6.4c.8 4.2.1 7.8-.6 10c1.5-1.2 3.1-2.4 4.9-3.6c1.2-2.3 2.7-7-.7-12.2c-1-1.6.3-1.7.8-1.6c1.7.5 4.2 6.6 2.8 11.9c7-5 4.5-11.9 6.2-11.9c2.1 0 1 7.7-2 11.5c-1 1.2-2.9 2.6-5.1 4c1.8.8 5.1 1.4 8.4-1.5c.4-.3 1.8-1.1 1.8.7s-5.9 6.6-12.5 2.3c-2.8 1.9-5.6 4-6.8 6.2l-5.8 5.2c.6-3 2.5-5.8 5.2-8.5");
}

.xkheykrbh {
  fill: var(--svg-color--d3976e, #d3976e);
  d: path("M27.5 35.7s0-15.3-14.5-15.3c-.1 0 0 15.3 14.5 15.3");
}

.xmxyh1b3k {
  d: path("M23.6 37c-.1.2 1.8 1.5 2.5 4c.8 2.4-.1 4.6.1 4.7c.2.2 1.5-2.1.7-4.9s-3.2-4-3.3-3.8m16.8 0c.1.2-1.8 1.5-2.5 4c-.8 2.4.1 4.6-.1 4.7c-.2.2-1.5-2.1-.7-4.9s3.2-4 3.3-3.8");
}

.yj4l7ybao {
  d: path("M48.6 22.6s-5.5 0-9.6 7.6c0 0 3.3-1.8 2.8-1s-2.9 2.6-.4 1.7c2.4-.9.8.7 0 1.5c-.8.7 7.2-1.5 7.2-9.8M35.7 59.2c.1.3-1.5 1.8-3.7 1.8c-2.3 0-3.9-1.6-3.7-1.8c.1-.3 1.7.6 3.7.6c2 .1 3.6-.9 3.7-.6");
}

.z10ug_d7e {
  cx: 40.4px;
  cy: 42.3px;
  rx: 2.4px;
  ry: 1.7px;
}

</style>
