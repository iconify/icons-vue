<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ajaah8bsi"/><path class="esf8f2b8y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:charger-private" /></template>
<style>
.ajaah8bsi {
  d: path("M14.33 20.5H6.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T5.12 20.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257v-6.164q0-.285.061-.563t.181-.537q.119-.258.291-.485t.389-.412l5.875-5.011q.088-.075.183-.142q.094-.067.194-.126t.205-.108t.214-.09q.108-.04.22-.07t.226-.051q.114-.02.23-.03q.115-.01.231-.01t.231.01t.23.03t.226.051t.22.07q.109.041.214.09t.205.108t.194.126t.183.142l5.875 5.011q.217.185.389.412t.291.485q.12.259.181.537t.061.563v1.627");
}

.esf8f2b8y {
  d: path("m17.447 15.013l-1.737 2.085a.703.703 0 0 0 .54 1.152a1.3 1.3 0 0 1 1.288 1.485L17.5 20a.476.476 0 0 0 .845.363l1.726-2.186A.727.727 0 0 0 19.5 17a1.287 1.287 0 0 1-1.272-1.483l.022-.142a.457.457 0 0 0-.803-.362");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
