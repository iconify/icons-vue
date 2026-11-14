<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="za2w2obmi"/><path class="xap845bpf"/><path class="pr-xiqbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:card-spinner" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pr-xiqbis {
  d: path("M16.75 13.5L18 14.75L16.75 16m2.5 3.5L18 20.75L19.25 22");
}

.xap845bpf {
  d: path("M9.5 14C7.75 12.75 6 11.5 6 9.5c0-1.25 1-2.25 2.25-2.25c.5 0 1 .25 1.25.75c.25-.5.75-.75 1.25-.75C12 7.25 13 8.25 13 9.5c0 2-1.75 3.25-3.5 4.5m10 1.152A3 3 0 0 1 18 20.75m-1.5-.402A3 3 0 0 1 18 14.75");
}

.za2w2obmi {
  d: path("M12.511 20H6.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T5.12 19.8q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257V5.625q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T3.7 4.62q.049-.119.11-.232t.132-.221q.072-.108.154-.207q.082-.1.173-.191t.191-.173t.207-.154t.221-.132t.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q5.996 3 6.125 3h6.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087q.119.049.232.11t.221.132t.207.154t.191.173t.173.191t.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25t.037.255q.013.128.013.257v5.332M15.5 4h1.75q.098 0 .195.019t.188.057t.173.093q.081.054.151.124t.124.151q.055.082.093.173t.057.188t.019.195v6.136");
}

</style>
