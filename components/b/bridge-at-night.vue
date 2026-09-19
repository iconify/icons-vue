<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="j_edqwb9w"/><path class="ylfz1om3e"/><path class="q7dzc7b5n"/><circle class="k83i-6b9r"/><g class="j9357eg9x"><circle class="hx0mrq3jd"/><circle class="icf3axbce"/><circle class="v_o8b0bdt"/><circle class="olbmqt1sl"/></g><path class="yu81j8bur"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:bridge-at-night" /></template>
<style>
.hx0mrq3jd {
  cx: 35px;
  cy: 9px;
  r: 2px;
}

.icf3axbce {
  cx: 29px;
  cy: 15px;
  r: 2px;
}

.j_edqwb9w {
  fill: var(--svg-color--42ade2, #42ade2);
  d: path("M0 0h64v64H0z");
}

.j9357eg9x {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
}

.k83i-6b9r {
  cx: 32px;
  cy: 12px;
  r: 8px;
  fill: var(--svg-color--fff, #fff);
}

.olbmqt1sl {
  cx: 35px;
  cy: 15px;
  r: 1px;
}

.q7dzc7b5n {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M64 28.9v-2c-4.8-.5-9.1-3-12-6.6V10h-6v10.3c-3.3 4.1-8.3 6.7-14 6.7s-10.7-2.6-14-6.7V10h-6v10.3c-2.9 3.6-7.2 6.1-12 6.6v2c1.7-.2 3.4-.6 5-1.2V34H0v6h9l1.2 6H12v6h6v-6h1.8l1.2-6h22l1.2 6H46v6h6v-6h1.8l1.2-6h9v-6h-5v-6.3c1.6.6 3.3 1 5 1.2m-18-5.7V28c0 3-2.2 5.4-5 5.9v-7.1c1.8-.9 3.5-2.1 5-3.6m-23 3.6v7.1c-2.8-.5-5-2.9-5-5.9v-4.8c1.5 1.5 3.1 2.7 5 3.6m-11-3.5V28c0 3-2.2 5.4-5 5.9v-7.1c1.9-.9 3.5-2.1 5-3.5M25 34v-6.3q2.85 1.05 6 1.2v5h-6zm8 0v-5q3.15-.15 6-1.2V34zm24-.1c-2.8-.5-5-2.9-5-5.9v-4.7c1.5 1.4 3.2 2.6 5 3.6z");
}

.v_o8b0bdt {
  cx: 29px;
  cy: 9px;
  r: 1px;
}

.ylfz1om3e {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M0 52h64v12H0z");
}

.yu81j8bur {
  fill: var(--svg-color--fff, #fff);
  d: path("M40 53c0 .6-.5 1-1 1H25c-.6 0-1-.4-1-1c0-.5.4-1 1-1h14c.5 0 1 .5 1 1m-2 4c0 .6-.5 1-1 1H27c-.6 0-1-.4-1-1c0-.5.4-1 1-1h10c.5 0 1 .5 1 1m-2 4c0-.5-.5-1-1-1h-6c-.6 0-1 .5-1 1c0 .6.4 1 1 1h6c.5 0 1-.4 1-1M2.7 4.976l.991-.99l.99.992l-.992.989zm3.381 9.627l.991-.989l.99.991l-.992.99zM19.483 4.496l.991-.989l.989.991l-.99.989zM39 19.604l.991-.99l.989.992l-.99.989zM57.176 4.48l.99-.99l.99.991l-.991.99zm2.407 39.91l.991-.99l.989.992l-.99.989zM36.01 48l.99-.99l.989.991l-.99.99zm-9.02-3.593l.991-.989l.99.991l-.992.99zM5.096 47.596l.991-.989l.989.991l-.991.99zM53.697 12.97l.99-.988l.99.99l-.991.99zm5.49 4.604l.991-.989l.99.991l-.992.99z");
}

</style>
