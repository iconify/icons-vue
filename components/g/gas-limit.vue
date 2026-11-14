<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="vkryt2b_g"/><path class="dzug2z5ob"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:gas-limit" /></template>
<style>
.dzug2z5ob {
  d: path("M12.5 8.5h2A1.5 1.5 0 0 1 16 10v3a1.5 1.5 0 0 0 3 0V7.5L16.5 5M7.75 6.25h.5a1.5 1.5 0 0 1 1.5 1.5v.5a1.5 1.5 0 0 1-1.5 1.5h-.5a1.5 1.5 0 0 1-1.5-1.5v-.5a1.5 1.5 0 0 1 1.5-1.5M15 18h6");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.vkryt2b_g {
  d: path("M12.241 18.011q-.079.166-.182.32q-.102.154-.225.291q-.123.138-.264.257t-.297.218q-.156.098-.325.174q-.168.075-.346.126t-.36.077t-.367.026h-3.75q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T5.12 19.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257V5.625q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T3.7 4.62q.049-.119.11-.232t.132-.221q.072-.108.154-.207q.082-.1.173-.191t.191-.173t.207-.154t.221-.132t.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q5.996 3 6.125 3h3.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087q.119.049.232.11t.221.132t.207.154t.191.173t.173.191t.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25t.037.255q.013.128.013.257v11.132M2.5 19.5h10.1");
}

</style>
