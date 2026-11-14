<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iyt2ceb0g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:data-source-error" /></template>
<style>
.iyt2ceb0g {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5v4m5-4v4m-.303 8.583Q11.138 15.5 10 15.5q-.147 0-.294-.007q-.148-.007-.294-.022q-.147-.014-.292-.036q-.146-.022-.291-.05q-.144-.029-.287-.065t-.284-.078t-.279-.093q-.139-.049-.275-.106t-.269-.119q-.133-.063-.263-.132q-.13-.07-.257-.146q-.126-.075-.248-.157q-.123-.082-.241-.17q-.119-.087-.232-.181q-.114-.093-.223-.192t-.214-.203q-.104-.105-.203-.214t-.192-.223q-.094-.113-.181-.232q-.088-.118-.17-.241q-.082-.122-.157-.248q-.076-.127-.146-.257t-.132-.263t-.119-.269t-.106-.275t-.093-.279q-.042-.141-.078-.284t-.065-.287t-.05-.291q-.022-.145-.036-.292q-.015-.146-.022-.294Q4 9.647 4 9.5v-3h12v3q0 .7-.161 1.382q-.162.682-.476 1.308M10 15.5v6m5-6.5l6 6m0-6l-6 6");
}

</style>
