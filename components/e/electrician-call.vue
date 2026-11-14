<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sd_rg4jzw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:electrician-call" /></template>
<style>
.sd_rg4jzw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M14.485 17.461q-.585.266-1.213.403Q12.643 18 12 18q-.147 0-.294-.007q-.148-.007-.294-.022q-.147-.014-.292-.036q-.146-.022-.291-.05q-.144-.029-.287-.065t-.284-.078q-.141-.043-.279-.093q-.139-.049-.275-.106t-.269-.119q-.133-.063-.263-.132q-.13-.07-.257-.146q-.126-.075-.248-.157q-.123-.082-.241-.17q-.119-.087-.232-.181q-.114-.093-.223-.192t-.214-.203q-.104-.105-.203-.214t-.192-.223q-.094-.113-.181-.232q-.088-.118-.17-.241q-.082-.122-.157-.248q-.076-.127-.146-.257t-.132-.263t-.119-.269t-.106-.275t-.093-.279q-.042-.141-.078-.284t-.065-.287t-.05-.291q-.022-.145-.036-.292q-.015-.146-.022-.294Q6 12.147 6 12V8.5h12V12l-.001.093M12 18v2.1M9.5 8.5v-5m5 5v-5m6.72 12.903a2 2 0 1 1-1.623-1.623M15 21l2.75-2.75");
}

</style>
