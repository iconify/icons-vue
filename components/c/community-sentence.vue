<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="zenl57rjq"/><path class="x5qw4-o_a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:community-sentence" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.x5qw4-o_a {
  d: path("m17.396 12.422l3.182 3.182a1.5 1.5 0 0 1 0 2.121l-.353.353a1.5 1.5 0 0 1-2.121 0l-3.182-3.182a1.5 1.5 0 0 1 0-2.121l.353-.353a1.5 1.5 0 0 1 2.121 0M16.5 16.5l-3 3");
}

.zenl57rjq {
  d: path("M10.724 19H5.125q-.129 0-.257-.013q-.129-.012-.255-.037q-.127-.026-.25-.063T4.12 18.8q-.119-.049-.232-.11t-.221-.132t-.207-.154t-.191-.173q-.091-.091-.173-.191q-.082-.099-.154-.207q-.071-.107-.132-.221q-.061-.113-.11-.232q-.05-.12-.087-.243t-.063-.25q-.025-.126-.037-.255q-.013-.128-.013-.257v-5.684q0-.281.059-.555q.06-.274.176-.529q.115-.256.283-.481t.378-.41l5.375-4.703q.089-.078.184-.147q.096-.07.197-.13q.101-.061.208-.112t.216-.093q.111-.042.225-.073t.23-.053t.233-.031q.118-.011.236-.011t.236.011q.117.01.233.031q.116.022.23.053t.225.073t.216.093q.107.051.208.112q.101.06.197.13q.095.069.184.147l5.375 4.703q.442.387.677.926");
}

</style>
