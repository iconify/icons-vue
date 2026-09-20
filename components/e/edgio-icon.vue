<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><radialGradient id="SVGvx7f8gav" cx="104.362%" cy="13.088%" r="94.575%" fx="104.362%" fy="13.088%"><stop offset="0%" class="qqtnx8_yz"/><stop offset="100%" class="vuxfoacrq"/></radialGradient><radialGradient id="SVGxBDsmcEU" cx="68.749%" cy="120.916%" r="68.487%" fx="68.749%" fy="120.916%"><stop offset="0%" class="yqw93kbdr"/><stop offset="100%" class="w7eyc5bqt"/></radialGradient><linearGradient id="SVGkj8Clhds" x1="3.185%" x2="57.325%" y1="2.866%" y2="58.917%"><stop offset="0%" class="pogri85fz"/><stop offset="100%" class="nodhq-b0t"/></linearGradient></defs><path fill="url(#SVGkj8Clhds)" class="tmbkaq7lv"/><path fill="url(#SVGvx7f8gav)" class="tmbkaq7lv"/><path fill="url(#SVGxBDsmcEU)" class="tmbkaq7lv"/><path class="h7kffwycz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:edgio-icon" /></template>
<style>
.h7kffwycz {
  fill: var(--svg-color--fff, #fff);
  d: path("m170.908 77.201l16.225-29.253H68.867v160.103h118.266l-16.144-29.293h-70.24v-36.819h55.755l8.983-29.294h-64.738V77.201z");
}

.nodhq-b0t {
  stop-color: var(--svg-color--6144a1, #6144a1);
}

.pogri85fz {
  stop-color: var(--svg-color--793092, #793092);
}

.qqtnx8_yz {
  stop-color: var(--svg-color--01b07d, #01b07d);
}

.tmbkaq7lv {
  d: path("M0 0h256v256H0z");
}

.vuxfoacrq {
  stop-color: var(--svg-color--01b07d, #01b07d);
  stop-opacity: 0;
}

.w7eyc5bqt {
  stop-color: var(--svg-color--00aae5, #00aae5);
  stop-opacity: 0;
}

.yqw93kbdr {
  stop-color: var(--svg-color--00aae5, #00aae5);
}

</style>
