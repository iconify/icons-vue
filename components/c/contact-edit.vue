<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ez75y5vzz"/><path class="l95wwccaz"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:contact-edit" /></template>
<style>
.ez75y5vzz {
  d: path("M8.311 21.5H7.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T6.12 21.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257V5.125q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T4.7 4.12q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h6.25q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087q.119.049.232.11t.221.132t.207.154t.191.173t.173.191t.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25t.037.255q.013.128.013.257v4.232M2.75 6.5h3.5M2.75 12h3.5m-3.5 5.5h3.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l95wwccaz {
  d: path("M16 3.75h2.5v2.5H16M16 9h2.5v.1m.243 3.157za1.5 1.5 0 0 1 0 2.122l-5.363 5.363a1.5 1.5 0 0 1-.697.394l-1.011.253a.875.875 0 0 1-1.061-1.061l.253-1.011a1.5 1.5 0 0 1 .394-.697l5.363-5.363a1.5 1.5 0 0 1 2.122 0");
}

</style>
