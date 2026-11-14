<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="j740ugqut"/><path class="ut0ur2bwg"/><path class="br6vtabco"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:counteroffer" /></template>
<style>
.br6vtabco {
  d: path("m13.75 19.5l1.5 1.5l1.5-1.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j740ugqut {
  d: path("M10.983 19.861q-.38-.076-.723-.259q-.342-.184-.616-.458l-5.875-5.875q-.183-.183-.326-.398t-.243-.454q-.099-.238-.15-.492q-.05-.253-.05-.512V5.625q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25T3.2 4.62q.049-.119.11-.232t.132-.221t.154-.207t.173-.191t.191-.173q.099-.082.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q5.496 3 5.625 3h5.788q.259 0 .512.05q.254.051.492.15q.239.099.454.243q.215.143.398.326l5.875 5.875q.114.114.214.242t.182.266t.149.287t.112.303q.047.155.074.315q.027.159.035.321q.007.161-.005.323q-.012.161-.044.319");
}

.ut0ur2bwg {
  d: path("M5.75 7.5a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0m15 14v-4.25a2.75 2.75 0 0 0-5.5 0V21");
}

</style>
