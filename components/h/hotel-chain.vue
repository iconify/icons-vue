<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zlsh2xnuv"/><path class="z4rkzkwtr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hotel-chain" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.z4rkzkwtr {
  d: path("M8.25 21.5v-4h3v.9m0 .2v2.9M7 6.5h.01m5.49 0h.01M7 11h.01m5.49 0h.01m3.99 5.5H16a2 2 0 0 0 0 4h.5m3-4h.5a2 2 0 0 1 0 4h-.5m-3-2h3");
}

.zlsh2xnuv {
  d: path("M12.311 21.5H6.625q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T5.62 21.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255Q4 19.004 4 18.875V5.125q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T4.2 4.12q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h6.25q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087q.119.049.232.11t.221.132t.207.154t.191.173t.173.191t.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25t.037.255q.013.128.013.257v8.632");
}

</style>
