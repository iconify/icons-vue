<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="abbrxle-t"/><path class="nyav735rf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:intruder-alert" /></template>
<style>
.abbrxle-t {
  d: path("M15.43 20H5.625q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.62 19.8q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255Q3 17.504 3 17.375v-6.164q0-.285.061-.563t.181-.537q.119-.258.291-.485t.389-.412l5.875-5.011q.088-.075.183-.142q.094-.067.194-.126t.205-.108t.214-.09t.22-.07t.226-.051q.114-.02.23-.03q.115-.01.231-.01t.231.01t.23.03t.226.051q.112.03.22.07q.109.041.214.09t.205.108t.194.126t.183.142l5.875 5.011q.217.185.389.412t.291.485q.12.259.181.537t.061.563v1.327");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.nyav735rf {
  d: path("M9.25 10.5a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M8 20c0-2.5 1.5-4.25 3.5-4.25S15 17.5 15 20m3-5.5V18m0 3h.01");
}

</style>
