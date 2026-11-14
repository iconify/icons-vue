<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="svvhc_blm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:approach-sequence" /></template>
<style>
.svvhc_blm {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("m14.147 13.667l-.748-.039a1.5 1.5 0 0 1-.782-.27l-1.1-.77a1.5 1.5 0 0 0-1.292-.208l-4.404 1.322a1.5 1.5 0 0 1-1.291-.208l-.019-.013a.475.475 0 0 1 .037-.801l2.395-1.364a1.107 1.107 0 0 0 .087-1.869l-.858-.601a1.5 1.5 0 0 0-1.253-.219l-.845.229a.8.8 0 0 1-.669-.116a.313.313 0 0 1-.04-.479L4.891 6.75a1.5 1.5 0 0 0 .308-.439l.897-1.951a.313.313 0 0 1 .464-.126a.8.8 0 0 1 .339.589l.073.872a1.5 1.5 0 0 0 .634 1.103l.858.601a1.107 1.107 0 0 0 1.727-.722l.462-2.717a.475.475 0 0 1 .741-.309l.018.013a1.5 1.5 0 0 1 .638 1.143l.264 4.591a1.5 1.5 0 0 0 .637 1.142l1.1.77a1.5 1.5 0 0 1 .52.643l.293.69a.737.737 0 0 1-.717 1.024M9 20.5h12.5");
}

</style>
