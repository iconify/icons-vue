<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="mpon77mfv"/><path class="bxa-uqymt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bridal-shower" /></template>
<style>
.bxa-uqymt {
  d: path("M18 21.25L15 18a1.9 1.9 0 0 1 3-2.25A1.9 1.9 0 0 1 21 18Z");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mpon77mfv {
  d: path("M4.75 5.5h14.5A1.75 1.75 0 0 1 21 7.25v.5a1.75 1.75 0 0 1-1.75 1.75H4.75A1.75 1.75 0 0 1 3 7.75v-.5A1.75 1.75 0 0 1 4.75 5.5M12.411 19H7.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T6.12 18.8q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257v-4.25q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25t.087-.243q.049-.119.11-.232t.132-.221t.154-.207q.082-.1.173-.191t.191-.173t.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037q.128-.013.257-.013h9.75q.129 0 .257.013q.129.012.255.037q.127.026.25.063t.243.087t.232.11t.221.132t.207.154q.1.082.191.173t.173.191q.082.099.154.207q.071.107.132.221q.061.113.11.232q.05.12.087.243t.063.25q.025.126.037.255q.013.128.013.257v.132M12 5.5v10.4m0 1.9V19m0-13.5C10.5 2 6.5 2 7 4c.3 1.2 2.5 1.5 5 1.5m0 0C13.5 2 17.5 2 17 4c-.3 1.2-2.5 1.5-5 1.5");
}

</style>
