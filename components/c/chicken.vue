<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="gcfqoacgh"/><path class="ezv1zj6-n"/><path class="cwzz1wbzu"/><g class="va15n-rxq"><path class="de4t62bkp"/><path class="kf2eevbnn"/></g><path class="wltjazb3u"/><g class="jeunsn1yj"><ellipse class="tl9px-bjr"/><circle class="vyhndvb3n"/></g><g class="bawg8-b1g"><path class="zy5c_yb2v"/><path class="pv0vrhbja"/></g><path class="yqj9eqfen"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:chicken" /></template>
<style>
.bawg8-b1g {
  fill: var(--svg-color--e24b4b, #e24b4b);
}

.cwzz1wbzu {
  fill: var(--svg-color--f4bc58, #f4bc58);
  d: path("M35.7 62H21.4c0-1.2 8.4-1.4 8.8-9.4c1.3 8.9 5.5 8.2 5.5 9.4");
}

.de4t62bkp {
  d: path("M49.4 30.6c0 11.5-9.4 23.3-21 23.3s-21-11.8-21-23.3c0-7.7 16.6-2.3 21-2.3c11.6-.1 21-9.3 21 2.3");
}

.ezv1zj6-n {
  fill: var(--svg-color--e1eaf2, #e1eaf2);
  d: path("M42.8 10.2c-7.7 4.5-1.3 15.3-15.2 18.2l14.8 7.3c3 5.2 11.3 5.6 11.3 5.6s2.1-6.2.4-10.8c4.6 0 7.8-2.8 7.8-2.8s-2.6-9.2-10.5-9.2c7.8-3.2 9.2-9.8 9.2-9.8s-6.9-4.8-17.8 1.5");
}

.gcfqoacgh {
  fill: var(--svg-color--f29a2e, #f29a2e);
  d: path("M7.6 20.4c1.8 2.9 3.8 3.3 5.2 1.6c2.2-2.6-.2-5.9-2.8-6.8c-4.3-1.7-8 3.1-8 3.1s4.1-.4 5.6 2.1");
}

.jeunsn1yj {
  fill: var(--svg-color--3e4347, #3e4347);
}

.kf2eevbnn {
  d: path("M36.4 49.2c0 2.3-3.3 7.3-6.2 7.3S24 53.1 24 50.8s12.4-2.7 12.4-1.6");
}

.pv0vrhbja {
  d: path("M20.8 10.6V9.4c-.2-2.5 3.4-3.5 3-4.8c-.6-1.7-5.3-.6-7.6 3.1q-.45.6-.6 1.5c-.1-.4-.2-.8-.4-1.2c-1.1-2.3 2.2-4.4 1.2-5.5c-1.3-1.5-5.2 1.1-6.1 5.4c-.2.9-.2 1.8.1 2.7c-.1-.1-.2-.2-.3-.2c-1.7-1.3 0-4-1.2-4.6c-1.8-.8-3.4 2.8-2.5 6.3c.6 2 2.8 4.1 4.6 2.4c.6-.5 2-1.3 2.8-1.6c.6-.2 2.2-.1 3.2.6c.9.6 1.6 1.8 2.9 1.8c5.7.2 8.8-5.3 6.7-6.5c-1.1-.8-2.8 1.2-5.8 1.8");
}

.tl9px-bjr {
  cx: 6.5px;
  cy: 16.1px;
  rx: 0.7px;
  ry: 0.3px;
}

.va15n-rxq {
  fill: var(--svg-color--d1dce6, #d1dce6);
}

.vyhndvb3n {
  cx: 11.5px;
  cy: 16.7px;
  r: 1.5px;
}

.wltjazb3u {
  fill: var(--svg-color--e1eaf2, #e1eaf2);
  d: path("M6.5 26.3c0 3 .6 11.7.6 11.7l2.7-3.4l3.2 3.8l.7-5.3l4.9 3.5l-.9-5.2l5.9.6l-2.7-3.2l4.1-2.7s-5 1.1-4.9-2s2.6-11.9-.5-13.2C13.9 8.8 6.5 13.6 6.5 26.3");
}

.yqj9eqfen {
  fill: var(--svg-color--e1eaf2, #e1eaf2);
  d: path("M42.5 43.9c-.9-2.2-3.5-3.4-3.5-3.4c2.7-1.4 4.3-4.4 4.3-4.4c-1.4-.6-6.8-1-6.8-1c1.2-1.2 2.2-2.9 2.2-2.9s-6.2-1.5-11.4 1.3c-6.8 3.8-4.8 12.8 2.9 13.8c8.5 1.1 12.3-3.4 12.3-3.4");
}

.zy5c_yb2v {
  d: path("M7.8 23.6c0 3.2-2.1.9-2.1.9c-.7 0-3.6 2.2-2.6-1.5c1.3-4.8 6.3-8 6.3-8s-1.6 2.8-1.6 8.6");
}

</style>
