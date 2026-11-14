<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="k0h8a0fpg"/><path class="zzui3qiko"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:account-fee-waived" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k0h8a0fpg {
  d: path("m5.784 14.284l-2.015-2.015q-.183-.183-.326-.398t-.243-.454q-.099-.238-.15-.492q-.05-.253-.05-.512V5.625q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T3.2 4.62q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q5.496 3 5.625 3h4.788q.259 0 .512.05q.254.051.492.15q.239.099.454.243q.215.143.398.326l1.982 1.982m3.96 3.96l.933.933q.091.091.173.191t.153.207t.133.221q.061.113.11.233q.049.119.087.242t.062.25q.025.126.038.255q.013.128.013.257t-.013.257t-.038.255t-.062.25t-.087.242t-.11.233t-.133.221q-.071.107-.153.207t-.173.191l-4.788 4.788q-.091.091-.191.173t-.207.153t-.221.133q-.113.061-.233.11q-.119.049-.242.087t-.25.062q-.126.025-.255.038q-.128.013-.257.013t-.257-.013t-.255-.038t-.25-.062t-.242-.087t-.233-.11t-.221-.133q-.107-.071-.207-.153t-.191-.173l-.9-.9");
}

.zzui3qiko {
  d: path("M5.75 7.25a1.5 1.5 0 1 0 3 0a1.5 1.5 0 1 0-3 0m8.72 6.218c.443.345.752.817.78 1.532c-.11.85-1.01 1.56-2.25 1.5a3.1 3.1 0 0 1-1.289-.19M13 16.5V18m-9.5 2.5l17-17");
}

</style>
