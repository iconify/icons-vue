<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="q6ojbxk4k"/><path class="knpqv1ipd"/><path class="pr-xiqbis"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bag-carousel" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.knpqv1ipd {
  d: path("M16.5 20.348A3 3 0 0 1 18 14.75");
}

.pr-xiqbis {
  d: path("M16.75 13.5L18 14.75L16.75 16m2.5 3.5L18 20.75L19.25 22");
}

.q6ojbxk4k {
  d: path("M13.511 21.5H6.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T5.12 21.3q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257v-7.25q0-.129.013-.257q.012-.129.037-.255q.026-.127.063-.25t.087-.243q.049-.119.11-.232t.132-.221q.072-.108.154-.207q.082-.1.173-.191t.191-.173t.207-.154q.107-.071.221-.132q.113-.061.232-.11q.12-.05.243-.087t.25-.063t.255-.037Q5.996 9 6.125 9h9.25q.109 0 .217.009t.216.027t.212.045q.106.026.209.062q.102.035.202.079t.195.095q.096.052.187.112q.091.059.176.126q.086.067.166.141t.154.154t.14.166t.126.177t.111.187t.095.195t.078.202t.062.209M5.5 9V6.5a2 2 0 0 1 4 0V9M12 9V6.5a2 2 0 0 1 4 0V9m3.5 6.152A3 3 0 0 1 18 20.75");
}

</style>
