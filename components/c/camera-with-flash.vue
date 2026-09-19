<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="kh-9i_loq"/><path class="fjhaq-4uw"/><path class="u-8kq0kga"/><path class="b5i9wt50a"/><path class="u4fh1rb8t"/><path class="iaycw5hsw"/><path class="e1_yw6rrp"/><circle class="nv0i6brix"/><circle class="y7y3zx1-p"/><g class="aaj16gswv"><path class="l5riqjbly"/><circle class="bl5jdd5hd"/><circle class="orltkxbnn"/></g><path class="mlh_7-_-o"/><circle class="qfrjrfb3d"/><path class="g3ghzknbx"/><path class="yxweeeb-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:camera-with-flash" /></template>
<style>
.aaj16gswv {
  fill: var(--svg-color--f5f5f5, #f5f5f5);
}

.b5i9wt50a {
  fill: var(--svg-color--51575b, #51575b);
  d: path("M51.7 28.8H23.8l2.8-15.3c.2-.9 1.4-2.2 2.1-2.5c4.3-1.9 13.9-1.9 18.1 0c.7.3 1.9 1.7 2.1 2.5z");
}

.bl5jdd5hd {
  cx: 35.1px;
  cy: 47.5px;
  r: 2.7px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.e1_yw6rrp {
  fill: var(--svg-color--212528, #212528);
  d: path("M54.8 44.8c0 9.4-7.6 17-17 17s-17-7.6-17-17s7.6-17 17-17s17 7.6 17 17");
}

.fjhaq-4uw {
  fill: var(--svg-color--51575b, #51575b);
  d: path("M4.1 29.6c0-2.6 2.1-4.7 4.7-4.7h46.3c2.6 0 4.7 2.1 4.7 4.7V31H4.1z");
}

.g3ghzknbx {
  fill: var(--svg-color--fff, #fff);
  d: path("M46 17.4c0 1-.8 1.7-1.7 1.7H31.2c-1 0-1.7-.8-1.7-1.7v-1.8c0-1 .8-1.7 1.7-1.7h13.1c1 0 1.7.8 1.7 1.7z");
}

.iaycw5hsw {
  fill: var(--svg-color--788287, #788287);
  d: path("M56.9 44.8c0 10.6-8.6 19.2-19.2 19.2s-19.2-8.6-19.2-19.2s8.6-19.2 19.2-19.2c10.6.1 19.2 8.7 19.2 19.2");
}

.kh-9i_loq {
  fill: var(--svg-color--212528, #212528);
  d: path("M22.9 26c0 1-.8 1.9-1.9 1.9h-8.4c-1 0-1.9-.8-1.9-1.9v-2.4c0-1 .9-1.9 1.9-1.9H21c1 0 1.9.8 1.9 1.9zm34.1-.1c0 .6-.5 1-1 1h-4.5c-.6 0-1-.5-1-1v-1.3c0-.6.5-1 1-1H56c.6 0 1 .5 1 1zm2.9 30c0 2.6-2.1 4.7-4.7 4.7H8.9c-2.6 0-4.7-2.1-4.7-4.7v-1.4h55.7z");
}

.l5riqjbly {
  d: path("M47.9 38.9c0 2.4-1.9 4.3-4.3 4.3s-4.3-1.9-4.3-4.3s1.9-4.3 4.3-4.3s4.3 2 4.3 4.3");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.mlh_7-_-o {
  fill: var(--svg-color--636c72, #636c72);
  d: path("M17.2 51.5c0 1-.8 1.9-1.9 1.9H7.2c-1 0-1.9-.8-1.9-1.9V34.6c0-1 .8-1.9 1.9-1.9h8.1c1 0 1.9.8 1.9 1.9z");
}

.nv0i6brix {
  cx: 37.8px;
  cy: 44.8px;
  r: 13.8px;
  fill: var(--svg-color--3e4347, #3e4347);
}

.orltkxbnn {
  cx: 30.3px;
  cy: 52.3px;
  r: 1.6px;
  opacity: var(--svg-opacity--0-5, 0.5);
}

.qfrjrfb3d {
  cx: 12.9px;
  cy: 28.2px;
  r: 2.8px;
  fill: var(--svg-color--212528, #212528);
}

.u-8kq0kga {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M4.1 30.8h55.7v24.6H4.1z");
}

.u4fh1rb8t {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M50.4 37.8H25.2l2.5-12.7c.2-.7 1.3-1.9 1.9-2.1c3.8-1.6 12.5-1.6 16.4 0c.6.3 1.7 1.4 1.9 2.1z");
}

.y7y3zx1-p {
  cx: 37.8px;
  cy: 44.8px;
  r: 7.5px;
  fill: var(--svg-color--212528, #212528);
}

.yxweeeb-m {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("m42.5 15.2l12-7.9l-2.2-2.9zm14 3.7v-3.4l-12.3 2.3zM45.1 0H41l-2.2 14.5zM33.6 15.2L23.4 4.4l-2.3 2.9zM33.9 0h-4.2l6.9 14.5zM18.7 15.5v3.4l12.9-1.1z");
}

</style>
