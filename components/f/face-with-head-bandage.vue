<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="ovapplgcj"/><g class="fbp0m0b1e"><circle class="wd2y6-jtg"/><circle class="j6u3aqw9p"/></g><path class="mfwi-acis"/><path class="pj_zki2vj"/><path class="l4cpjqbng"/><path class="g828l67yt"/><path class="x-h2ugb7j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:face-with-head-bandage" /></template>
<style>
.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.g828l67yt {
  fill: var(--svg-color--fff, #fff);
  d: path("M17 8.1c13.6-.1 27.6 4 39.8 9.6c3.3 6.5 3.5 11.9 3.5 11.9c-16.5-8.7-35.4-13.1-52.9-11.4c0 0 4.2-7.8 9.6-10.1");
}

.j6u3aqw9p {
  cx: 20.2px;
  cy: 30px;
  r: 5px;
}

.l4cpjqbng {
  fill: var(--svg-color--cccfd4, #cccfd4);
  d: path("M15.8 6.7c14.5-.1 28.9 3.3 41.9 9.8C60.4 21 62 26.3 62 32v1.4A92.96 92.96 0 0 0 4.5 20c2.4-5.5 6.4-10.1 11.3-13.3");
}

.mfwi-acis {
  fill: var(--svg-color--cccfd4, #cccfd4);
  d: path("M32 2c-6 0-11.7 1.8-16.4 4.9c17.7 9.1 33.2 23 41.7 41.2c3-4.6 4.7-10.2 4.7-16.1C62 15.4 48.6 2 32 2");
}

.ovapplgcj {
  cx: 31.9px;
  cy: 32.1px;
  r: 29.9px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.pj_zki2vj {
  fill: var(--svg-color--fff, #fff);
  d: path("M32.9 3.6C27.4 3.6 22.3 5.2 18 8c16.7 7.7 31.6 19.3 39.4 35.8c3.1-5.8 2.9-12.9 2.9-12.9C60.2 15.8 48 3.6 32.9 3.6");
}

.wd2y6-jtg {
  cx: 43.7px;
  cy: 30px;
  r: 5px;
}

.x-h2ugb7j {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M40.3 42.8c-5.8-1.5-12-.4-16.9 3c-1.2.9 1.1 4 2.3 3.2c3.2-2.3 8.4-3.8 13.7-2.4c1.3.3 2.4-3.3.9-3.8");
}

</style>
