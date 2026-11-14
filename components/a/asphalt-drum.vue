<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gj0o2vb1j"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:asphalt-drum" /></template>
<style>
.gj0o2vb1j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M13.511 21.5H6.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T5.12 21.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257V5.125q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T3.7 4.12q.049-.119.11-.232t.132-.221q.072-.108.154-.207q.082-.1.173-.191t.191-.173t.207-.154t.221-.132t.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h7.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087q.119.049.232.11t.221.132t.207.154t.191.173t.173.191t.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v6.232M3.5 7.5h13m-13 5h12.3m2.7.75c.5 2 3 3 3 5.25a3 3 0 0 1-6 0c0-1.5 1-2.5 1.5-3.25c.25 1 .75 1.5 1.25 1.5c.25-1 0-2.5.25-3.5");
}

</style>
