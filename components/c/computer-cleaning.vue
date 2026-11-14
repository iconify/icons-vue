<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="syljffg7u"/><path class="zthitrbkd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:computer-cleaning" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.syljffg7u {
  d: path("M13.499 18.951q-.004.127-.02.252q-.015.126-.043.249q-.028.124-.068.244q-.039.12-.09.236t-.113.226t-.134.215t-.154.2q-.082.097-.173.185t-.19.167t-.204.148t-.219.128q-.112.059-.229.106q-.117.048-.239.084t-.245.06q-.124.025-.25.037t-.253.012h-5.25q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.62 21.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255Q3 19.004 3 18.875V5.125q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T3.2 4.12q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h5.25q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087q.119.049.232.11t.221.132t.207.154t.191.173t.173.191t.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25t.037.255q.013.128.013.257v7.432M6 6.5h4.5M6 9.5h4.5m-2.25 7h.01m8.24 5v-3a1 1 0 0 1 1-1V14h3v3.5a1 1 0 0 1 1 1v3Z");
}

.zthitrbkd {
  d: path("M17.5 14.75h-2.25v2");
}

</style>
