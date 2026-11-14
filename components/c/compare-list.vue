<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nnbe6xbih"/><path class="kcw43x01m"/><path class="ydcdh_b1s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:compare-list" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kcw43x01m {
  fill: currentColor;
  d: path("M6 5h1a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 7 9.5H6a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 6 5m11 0h1a1.75 1.75 0 0 1 1.75 1.75v1A1.75 1.75 0 0 1 18 9.5h-1a1.75 1.75 0 0 1-1.75-1.75v-1A1.75 1.75 0 0 1 17 5");
}

.nnbe6xbih {
  d: path("M4.875 3h3.25a2.625 2.625 0 0 1 2.625 2.625v12.75A2.625 2.625 0 0 1 8.125 21h-3.25a2.625 2.625 0 0 1-2.625-2.625V5.625A2.625 2.625 0 0 1 4.875 3m8.375 9.28V5.625q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25t.087-.243q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q15.746 3 15.875 3h3.25q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11q.114.061.221.132q.108.072.207.154q.1.082.191.173t.173.191t.154.207t.132.221t.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v5.732M4.5 12h4m-4 2.75H7m8.5-3.25h1.6");
}

.ydcdh_b1s {
  d: path("M14 15h7.5m-2-2l2 2l-2 2m2 3H14m2-2l-2 2l2 2");
}

</style>
