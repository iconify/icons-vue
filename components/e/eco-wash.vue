<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="e-b4s9pip"/><path class="p1q44fbvq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eco-wash" /></template>
<style>
.e-b4s9pip {
  d: path("M12.3 20H3V2.5h16.5v9.8M3 5.75h16.5");
}

.p1q44fbvq {
  d: path("M14.538 14.553q.227-.414.345-.872T15 12.75q0-.184-.018-.368q-.018-.183-.054-.364q-.036-.18-.089-.357q-.054-.176-.124-.346t-.158-.333t-.189-.315q-.102-.154-.219-.296t-.247-.273t-.273-.247t-.296-.219t-.315-.189q-.163-.087-.333-.158q-.17-.07-.346-.124q-.177-.053-.357-.089q-.181-.036-.364-.054Q11.434 9 11.25 9t-.368.018t-.364.054t-.357.089t-.346.124t-.333.158t-.315.189q-.154.102-.296.219t-.273.247t-.247.273t-.219.296t-.189.315q-.087.163-.158.333q-.07.17-.124.346q-.053.177-.089.357q-.036.181-.054.364q-.018.184-.018.368t.018.368t.054.364t.089.357q.054.176.124.346t.158.333t.189.315q.102.154.219.296t.247.273t.273.247t.296.219t.315.189q.163.087.333.158q.17.07.346.124q.177.053.357.089q.181.036.364.054q.184.018.368.018q.341 0 .676-.061q.335-.062.653-.182q.319-.121.61-.297q.292-.177.547-.402M15 21.5c0-4.5 2-6.5 6.5-6.5c0 4.5-2 6.5-6.5 6.5Zm0 0l3.5-3.5");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

</style>
