<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="av8c7bb8u"/><path class="bb7tms6mo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:hotel-check" /></template>
<style>
.av8c7bb8u {
  d: path("M14.062 21.216q-.276.14-.577.212t-.61.072h-6.75q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T5.12 21.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257V5.125q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T3.7 4.12q.049-.119.11-.232t.132-.221q.072-.108.154-.207q.082-.1.173-.191t.191-.173t.207-.154t.221-.132t.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h6.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087q.119.049.232.11t.221.132t.207.154t.191.173t.173.191t.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25t.037.255q.013.128.013.257v10.132M7.25 7h.01m4.49 0h.01m-4.51 4.5h.01m4.49 0h.01");
}

.bb7tms6mo {
  d: path("M8 21.5V17h3v4.5m3.75-3.5l2 2L21 15.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
