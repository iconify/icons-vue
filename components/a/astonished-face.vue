<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><circle class="yp79zhbev"/><path class="w9b2e9b6g"/><path class="evmhh_bou"/><path class="mrf7t92tw"/><path class="ddvxb65ut"/><circle class="a3d_kcb6f"/><path class="wwt21-byt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:astonished-face" /></template>
<style>
.a3d_kcb6f {
  cx: 32px;
  cy: 49px;
  r: 9px;
  fill: var(--svg-color--664e27, #664e27);
}

.ddvxb65ut {
  fill: var(--svg-color--917524, #917524);
  d: path("M50.2 15.8c-3.2-2.7-7.5-3.9-11.7-3.1c-.6.1-1.1-2-.4-2.2c4.8-.9 9.8.5 13.5 3.6c.6.5-1 2.1-1.4 1.7m-24.7-3.3c-4.2-.7-8.5.4-11.7 3.1c-.4.4-2-1.2-1.4-1.7c3.7-3.2 8.7-4.5 13.5-3.6c.7.2.2 2.3-.4 2.2");
}

.evmhh_bou {
  fill: var(--svg-color--fff, #fff);
  d: path("M56 29c0 6.1-4.9 11-11 11s-11-4.9-11-11s4.9-11 11-11s11 4.9 11 11");
}

.mrf7t92tw {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M50 29c0 2.8-2.2 5-5 5s-5-2.2-5-5s2.2-5 5-5s5 2.2 5 5");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.w9b2e9b6g {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M24 29c0 2.8-2.2 5-5 5s-5-2.2-5-5s2.2-5 5-5s5 2.2 5 5");
}

.wwt21-byt {
  fill: var(--svg-color--fff, #fff);
  d: path("M26 46c1.2-2.4 3.4-4 6-4s4.8 1.6 6 4z");
}

.yp79zhbev {
  cx: 19px;
  cy: 29px;
  r: 11px;
  fill: var(--svg-color--fff, #fff);
}

</style>
