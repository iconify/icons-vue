<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="iygyghczd"/><path class="was__8r-g"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cpu-throttle" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.iygyghczd {
  d: path("M12.692 14.981q-.158.019-.317.019h-4.75q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T6.62 14.8q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173t-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25t-.037-.255Q5 12.504 5 12.375v-4.75q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T5.2 6.62q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q7.496 5 7.625 5h4.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087q.119.049.232.11t.221.132t.207.154q.1.082.191.173t.173.191t.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25t.037.255q.013.128.013.257v4.332M8.5 2.5V5m3-2.5V5m-3 10v2.5m3-2.5v2.5m-9-9H5m-2.5 3H5m10-3h2.5m-2.5 3h2.5");
}

.was__8r-g {
  d: path("M9.5 8h1A1.5 1.5 0 0 1 12 9.5v1a1.5 1.5 0 0 1-1.5 1.5h-1A1.5 1.5 0 0 1 8 10.5v-1A1.5 1.5 0 0 1 9.5 8m6 6.75l3 3l3-3m-6 3.75l3 3l3-3");
}

</style>
