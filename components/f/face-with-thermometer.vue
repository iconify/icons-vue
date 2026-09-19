<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><g class="fbp0m0b1e"><circle class="lknu7lb8f"/><circle class="zdgpe9b_x"/></g><path class="ldkoeybbz"/><path class="uu-t29jsu"/><path class="h6wq3zxwa"/><path class="dft-3pbmw"/><ellipse transform="rotate(-54.808 8.95 34.089)" class="k2z1n-75b"/><path class="car-xccei"/><path class="vs_3v87sb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:face-with-thermometer" /></template>
<style>
.car-xccei {
  fill: var(--svg-color--51575b, #51575b);
  d: path("m18.1 41.5l-2 2.8l-.9-.5l2-2.9zm2.4 1.7l-1.9 2.7l-.9-.5l1.9-2.8zm2.5 1.7l-1.9 2.6l-.8-.5l1.8-2.6zm2.4 1.7L23.8 49l-.9-.6l1.7-2.3zm2.5 1.7l-1.5 2.2l-.9-.6l1.5-2.1z");
}

.dft-3pbmw {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("m7.5 36.2l22.1 14.4l1.9-2.6l-21.1-16z");
}

.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.h6wq3zxwa {
  fill: var(--svg-color--fff, #fff);
  d: path("m5.8 36.5l23.8 15l2.8-3.9l-22.2-17.3c-3.7-2.6-8.1 3.6-4.4 6.2");
}

.k2z1n-75b {
  cx: 9px;
  cy: 34.1px;
  fill: var(--svg-color--a5203c, #a5203c);
  rx: 2.6px;
  ry: 0.9px;
}

.ldkoeybbz {
  fill: var(--svg-color--917524, #917524);
  d: path("M25.6 15.2c-3.2 2.7-7.5 3.9-11.7 3.1c-.6-.1-1.1 2-.4 2.2c4.8.9 9.8-.5 13.5-3.6c.5-.5-1-2.1-1.4-1.7m24.5 3c-4.2.7-8.5-.4-11.7-3.1c-.4-.4-2 1.2-1.4 1.7c3.7 3.2 8.7 4.5 13.5 3.6c.7-.2.2-2.3-.4-2.2");
}

.lknu7lb8f {
  cx: 43.5px;
  cy: 30.3px;
  r: 5px;
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.uu-t29jsu {
  fill: var(--svg-color--e5e5e5, #e5e5e5);
  d: path("m4.4 38.7l24.2 14.2l4.6-6.5l-21.4-18.1c-6.4-4.5-13.7 5.9-7.4 10.4");
}

.vs_3v87sb {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M41.5 43.9c-6 .3-11.6 3.3-15.2 8c-.9 1.2 2.2 3.5 3.1 2.3c2.4-3.1 6.8-6.2 12.3-6.5c1.4 0 1.3-3.8-.2-3.8");
}

.zdgpe9b_x {
  cx: 20.5px;
  cy: 30.3px;
  r: 5px;
}

</style>
