<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kyyd45b3n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:connector-add" /></template>
<style>
.kyyd45b3n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7.5 2.5v4m5-4v4m2.713 5.97q-.097.172-.206.336t-.228.322t-.249.307t-.269.289t-.287.271t-.304.252t-.32.231t-.335.209t-.348.188q-.177.087-.359.163t-.369.14t-.378.115q-.19.052-.384.09q-.194.039-.39.065q-.195.026-.392.039T10 15.5q-.147 0-.294-.007q-.148-.007-.294-.022q-.147-.014-.292-.036q-.146-.022-.291-.05q-.144-.029-.287-.065t-.284-.078t-.279-.093q-.139-.049-.275-.106t-.269-.119q-.133-.063-.263-.132q-.13-.07-.257-.146q-.126-.075-.248-.157q-.123-.082-.241-.17q-.119-.087-.232-.181q-.114-.093-.223-.192t-.214-.203q-.104-.105-.203-.214t-.192-.223q-.094-.113-.181-.232q-.088-.118-.17-.241q-.082-.122-.157-.248q-.076-.127-.146-.257t-.132-.263t-.119-.269t-.106-.275t-.093-.279q-.042-.141-.078-.284t-.065-.287t-.05-.291q-.022-.145-.036-.292q-.015-.146-.022-.294Q4 9.647 4 9.5v-3h12v3q0 1.147-.423 2.212M10 15.5v6m8-7v7M14.5 18h7");
}

</style>
