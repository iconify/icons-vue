<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="x7sq_v6gq"/><path class="p3rk_k9mp"/><path class="p45486bar"/><path class="x15tibb6w"/><path class="jwkl2gbdo"/><path class="tph1bb71a"/><path class="on7tqgb9t"/><circle class="lyc985bwr"/><circle class="l7ws5dbwu"/><g class="aaj16gswv"><path class="bs8jf-k-u"/><circle class="k13qsvuyi"/><circle class="babtkn86h"/></g><path class="m3u8s8_sh"/><circle class="nqx329x7c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:camera" /></template>
<style>
.aaj16gswv {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
}

.babtkn86h {
  cx: 30.1px;
  cy: 46.2px;
  r: 1.9px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.bs8jf-k-u {
  d: path("M50.3 30.9c0 2.7-2.2 4.9-4.9 4.9s-4.9-2.2-4.9-4.9s2.2-4.9 4.9-4.9c2.7-.1 4.9 2.2 4.9 4.9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.jwkl2gbdo {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M53.1 29.6h-29L27 15c.2-.8 1.5-2.1 2.2-2.4c4.4-1.8 14.4-1.8 18.8 0c.7.3 1.9 1.6 2.2 2.4z");
}

.k13qsvuyi {
  cx: 35.6px;
  cy: 40.7px;
  r: 3.1px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.l7ws5dbwu {
  cx: 38.6px;
  cy: 37.6px;
  r: 8.6px;
  fill: var(--svg-color--212528, #212528);
}

.lyc985bwr {
  cx: 38.6px;
  cy: 37.6px;
  r: 15.9px;
  fill: var(--svg-color--3e4347, #3e4347);
}

.m3u8s8_sh {
  fill: var(--svg-color--636c72, #636c72);
  d: path("M15 45.3c0 1.2-1 2.2-2.2 2.2H3.6c-1.2 0-2.2-1-2.2-2.2V25.9c0-1.2 1-2.2 2.2-2.2h9.2c1.2 0 2.2 1 2.2 2.2z");
}

.nqx329x7c {
  cx: 10.1px;
  cy: 18.6px;
  r: 3.2px;
  fill: var(--svg-color--212528, #212528);
}

.on7tqgb9t {
  fill: var(--svg-color--212528, #212528);
  d: path("M58.2 37.6c0 10.8-8.8 19.6-19.6 19.6S19 48.4 19 37.6S27.8 18 38.6 18c10.8.1 19.6 8.8 19.6 19.6");
}

.p3rk_k9mp {
  fill: var(--svg-color--51575b, #51575b);
  d: path("M0 20.1c0-3 2.4-5.4 5.4-5.4h53.1c3 0 5.4 2.4 5.4 5.4v1.6H0z");
}

.p45486bar {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M0 21.5h64v28.3H0z");
}

.tph1bb71a {
  fill: var(--svg-color--788287, #788287);
  d: path("M60.6 37.6c0 12.2-9.9 22-22 22s-22-9.8-22-22c0-12.1 9.9-22 22-22c12.2 0 22 9.9 22 22");
}

.x15tibb6w {
  fill: var(--svg-color--51575b, #51575b);
  d: path("M54.7 18H22.6l3.2-10.8c.3-.6 1.6-1.6 2.4-1.8C33.1 4 44.1 4 49 5.4c.8.2 2.1 1.2 2.4 1.8z");
}

.x7sq_v6gq {
  fill: var(--svg-color--212528, #212528);
  d: path("M21.6 16.1c0 1.2-1 2.2-2.2 2.2H9.7c-1.2 0-2.2-1-2.2-2.2v-2.7c0-1.2 1-2.2 2.2-2.2h9.7c1.2 0 2.2 1 2.2 2.2zm39.1-.2c0 .6-.5 1.2-1.2 1.2h-5.2c-.6 0-1.2-.5-1.2-1.2v-1.4c0-.6.5-1.2 1.2-1.2h5.2c.6 0 1.2.5 1.2 1.2zM64 50.3c0 3-2.4 5.4-5.4 5.4H5.4c-3 0-5.4-2.4-5.4-5.4v-1.6h64z");
}

</style>
