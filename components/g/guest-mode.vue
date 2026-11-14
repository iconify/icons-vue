<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dfjyjmbdo"/><path class="uhkruqb7c"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:guest-mode" /></template>
<style>
.dfjyjmbdo {
  d: path("M11.73 20.5H6.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T5.12 20.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257v-6.164q0-.285.061-.563t.181-.537q.119-.258.291-.485t.389-.412l5.875-5.011q.088-.075.183-.142q.094-.067.194-.126t.205-.108t.214-.09q.108-.04.22-.07t.226-.051q.114-.02.23-.03q.115-.01.231-.01t.231.01t.23.03t.226.051t.22.07q.109.041.214.09t.205.108t.194.126t.183.142l5.875 5.011q.19.162.346.357q.157.196.273.417t.189.46t.099.488M14.5 21.25c0-1.5 1.5-2.5 3.5-2.5s3.5 1 3.5 2.5c0 .25-.25.5-.5.5h-6c-.25 0-.5-.25-.5-.5");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.uhkruqb7c {
  d: path("M16.25 15.25a1.75 1.75 0 1 0 3.5 0a1.75 1.75 0 1 0-3.5 0");
}

</style>
