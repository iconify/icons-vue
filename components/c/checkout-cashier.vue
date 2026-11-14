<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fd-enr0es"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:checkout-cashier" /></template>
<style>
.fd-enr0es {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 3h4.5a1.75 1.75 0 0 1 1.75 1.75v1.5A1.75 1.75 0 0 1 10.75 8h-4.5A1.75 1.75 0 0 1 4.5 6.25v-1.5A1.75 1.75 0 0 1 6.25 3M8.5 8v3.5m4.011 7H5.625q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.62 18.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255Q3 16.004 3 15.875v-1.75q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25t.087-.243q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173t.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h7.75q.422 0 .823.132q.4.133.74.384M3.5 18.5v3h8m4.5-5.75a2 2 0 1 0 4 0a2 2 0 1 0-4 0m-1.75 6c0-1.75 1.75-3 3.75-3s3.75 1.25 3.75 3");
}

</style>
