<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zx5d1sb0k"/><path class="g0ms4_bks"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:carrier-unlock" /></template>
<style>
.g0ms4_bks {
  d: path("M8.75 7.5h3a1.75 1.75 0 0 1 1.75 1.75v3A1.75 1.75 0 0 1 11.75 14h-3A1.75 1.75 0 0 1 7 12.25v-3A1.75 1.75 0 0 1 8.75 7.5m8 10h2.5A1.75 1.75 0 0 1 21 19.25v.5a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 15 19.75v-.5a1.75 1.75 0 0 1 1.75-1.75m-.25 0v-1a1.5 1.5 0 0 1 3-.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zx5d1sb0k {
  d: path("M12.176 20H6.625q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T5.62 19.8q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255Q4 17.504 4 17.375V5.125q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T4.2 4.12q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h5.788q.259 0 .512.05q.254.051.492.15q.239.099.454.243q.215.143.398.326l2.962 2.962q.183.183.326.398t.243.454t.15.492t.05.512v3.805");
}

</style>
