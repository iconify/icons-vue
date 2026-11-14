<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="u4o3d4b1u"/><path class="rwsfu3ctj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:family-court" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.rwsfu3ctj {
  d: path("m13.5 18.5l1.25-2.75L16 18.5a1.25 1.25 0 0 1-2.5 0m6 0l1.25-2.75L22 18.5a1.25 1.25 0 0 1-2.5 0");
}

.u4o3d4b1u {
  d: path("M11.03 20.5H6.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T5.12 20.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257v-6.164q0-.285.061-.563t.181-.537q.119-.258.291-.485t.389-.412l5.875-5.011q.088-.075.183-.142q.094-.067.194-.126t.205-.108t.214-.09q.108-.04.22-.07t.226-.051q.114-.02.23-.03q.115-.01.231-.01t.231.01t.23.03t.226.051t.22.07q.109.041.214.09t.205.108t.194.126t.183.142l5.875 5.011q.217.185.389.412t.291.485q.12.259.181.537t.061.563v1.227M17.75 14v7.5m-1.5 0h3m-4.5-5.75h6");
}

</style>
