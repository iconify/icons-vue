<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="dubcufb5g"/><path class="c792zlkef"/><path class="mucf1nbsq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:bike-score" /></template>
<style>
.c792zlkef {
  d: path("M6.25 12.5h5l3.75-6l2.593 5.658");
}

.dubcufb5g {
  d: path("M2.5 12.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0m18.719 1.424q.281-.684.281-1.424q0-.184-.018-.368q-.018-.183-.054-.364q-.036-.18-.089-.357q-.054-.176-.124-.346t-.158-.333q-.087-.162-.189-.315q-.102-.154-.219-.296t-.247-.273t-.273-.247q-.142-.117-.296-.219q-.153-.102-.315-.189q-.163-.087-.333-.158q-.17-.07-.346-.124q-.177-.053-.357-.089q-.181-.036-.364-.054q-.184-.018-.368-.018t-.368.018q-.183.018-.364.054q-.18.036-.357.089q-.176.054-.346.124t-.333.158t-.315.189q-.154.102-.296.219t-.273.247t-.247.273t-.219.296t-.189.315q-.087.163-.158.333q-.07.17-.124.346q-.053.177-.089.357q-.036.181-.054.364q-.018.184-.018.368q0 .75.289 1.443");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mucf1nbsq {
  d: path("m6.25 12.5l3-6H15m-5.75 0v-2m-1.5 0h3m4.25 2l-.75-2h2.25m1.764 10.792l.166.335a1.5 1.5 0 0 0 1.129.821l.37.053a.574.574 0 0 1 .318.979l-.268.26a1.5 1.5 0 0 0-.431 1.328l.063.368a.574.574 0 0 1-.832.605l-.331-.174a1.5 1.5 0 0 0-1.396 0l-.331.174a.574.574 0 0 1-.832-.605l.063-.368a1.5 1.5 0 0 0-.431-1.328l-.268-.26a.574.574 0 0 1 .318-.979l.37-.053a1.5 1.5 0 0 0 1.129-.821l.166-.335a.574.574 0 0 1 1.028 0");
}

</style>
