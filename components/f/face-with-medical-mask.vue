<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="ylbe9m3hg"/><path class="jn4zatbbq"/><path class="mwgw_1a_m"/><path class="ob6tax38e"/><path class="f3qt-ugrg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:face-with-medical-mask" /></template>
<style>
.f3qt-ugrg {
  fill: var(--svg-color--917524, #917524);
  d: path("M53.2 17c-3.2-2.7-7.5-3.9-11.7-3.1c-.6.1-1.1-2-.4-2.2c4.8-.9 9.8.5 13.5 3.6c.6.5-1 2.1-1.4 1.7m-30.7-3.3c-4.2-.7-8.5.4-11.7 3.1c-.4.4-2-1.2-1.4-1.7c3.7-3.2 8.7-4.5 13.5-3.6c.7.2.2 2.3-.4 2.2");
}

.jn4zatbbq {
  d: path("M49.9 39.9c0 10.6-8 19.1-17.9 19.1s-17.9-8.6-17.9-19.1c0-10.6 10.4-8.5 17.9-8.5c7.5-.1 17.9-2.1 17.9 8.5");
  opacity: var(--svg-opacity--0-1, 0.1);
}

.mwgw_1a_m {
  fill: var(--svg-color--fff, #fff);
  d: path("M49.5 39.1c0 10-7.8 18-17.5 18s-17.5-8.1-17.5-18c0-10 10.2-8.1 17.5-8.1s17.5-1.9 17.5 8.1");
}

.ob6tax38e {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M35.8 20.8c2 8.8 10.2 11 16.3 4.4c.3-.3-.2-.6-.7-1.3c-4.9 2.1-11.4.1-14.3-3.8c-.8.2-1.4.2-1.3.7m-24 4.4c6.1 6.6 14.3 4.4 16.3-4.4c.1-.4-.5-.5-1.2-.7c-3.2 4.3-9.9 5.8-14.4 3.9c-.5.5-1 .8-.7 1.2");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.ylbe9m3hg {
  fill: var(--svg-color--fff, #fff);
  d: path("m18.2 47.4l-9 4.1c.8 1 1.7 1.9 2.6 2.7l7.6-3.6zm-1.1-12.3L2 31.7v.3c0 1.1.1 2.2.2 3.3l14.2 3.2zm37.7 16.4l-9-4.1l-1.3 3.3l7.6 3.6c1-.9 1.8-1.8 2.7-2.8m-7.1-13l14.2-3.2c.1-1.1.2-2.2.2-3.3v-.3L47 35.2z");
}

</style>
