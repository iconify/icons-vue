<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="pq0-d5xnn"/><path class="p5i9ptbdr"/><path class="fre1babwy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:crime-rate" /></template>
<style>
.fre1babwy {
  d: path("M11 8.25a1.5 1 0 1 0 3 0a1.5 1 0 1 0-3 0Zm4 13.25V19m3 2.5v-5m3 5v-7");
}

.p5i9ptbdr {
  d: path("M9.25 7.5a1.5 1 0 1 0 3 0a1.5 1 0 1 0-3 0Z");
}

.pq0-d5xnn {
  d: path("M2.25 6.5a3.75 3.75 0 1 0 7.5 0a3.75 3.75 0 1 0-7.5 0Zm17.316 5.235q.28-.263.501-.578q.222-.314.374-.667q.153-.353.231-.729q.078-.377.078-.761q0-.184-.018-.368q-.018-.183-.054-.364q-.036-.18-.089-.357q-.054-.176-.124-.346t-.158-.333q-.087-.162-.189-.315q-.102-.154-.219-.296t-.247-.273q-.131-.13-.273-.247t-.296-.219q-.153-.102-.315-.189q-.163-.087-.333-.158q-.17-.07-.346-.124q-.177-.053-.357-.089q-.181-.036-.364-.054q-.184-.018-.368-.018t-.368.018q-.183.018-.364.054q-.18.036-.357.089q-.176.054-.346.124t-.333.158t-.315.189q-.154.102-.296.219t-.273.247q-.13.131-.247.273t-.219.296t-.189.315q-.087.163-.158.333q-.07.17-.124.346q-.053.177-.089.357q-.036.181-.054.364q-.018.184-.018.368t.018.368t.054.364t.089.357t.124.346t.158.333t.189.315q.102.154.219.296t.247.273t.273.247t.296.219t.315.189q.163.087.333.158q.17.07.346.124q.177.053.357.089q.181.036.364.054q.184.018.368.018q.622 0 1.211-.201");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
