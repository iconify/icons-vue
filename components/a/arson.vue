<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="nc60z3pxg"/><path class="wtuyl5bes"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:arson" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nc60z3pxg {
  d: path("M12.162 18.5H5.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.12 18.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257V9.813q0-.152.018-.304q.017-.151.052-.299t.087-.292t.12-.279t.152-.264t.181-.244q.097-.117.208-.222t.232-.196l5.375-4.032q.085-.063.174-.12t.183-.105q.093-.049.19-.091q.098-.041.198-.074q.1-.034.203-.059q.102-.025.207-.042q.104-.017.209-.026t.211-.008t.211.008q.105.009.209.026q.105.017.207.042q.103.025.203.059t.198.074q.097.042.19.091q.094.049.183.105q.089.057.174.12l5.375 4.032q.122.091.232.196t.208.222t.181.244q.084.128.152.264t.12.279t.087.292t.052.299q.018.152.018.304v1.193");
}

.wtuyl5bes {
  d: path("M6.5 18.5V14h4v4.5m7.75 3.5c-2 0-3.25-1.5-3.25-3.25c0-1.5.75-2.5 1.25-3.5c.75.75 1 1.25 1 2.25c.75-1.25 1.25-2.5 1-3.75c2 1.25 3.25 3.25 3.25 5S20.25 22 18.25 22");
}

</style>
