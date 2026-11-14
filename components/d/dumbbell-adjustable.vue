<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="l0lld8amd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dumbbell-adjustable" /></template>
<style>
.l0lld8amd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M4.75 3zA2.25 2.25 0 0 1 7 5.25v5a2.25 2.25 0 0 1-2.25 2.25a2.25 2.25 0 0 1-2.25-2.25v-5A2.25 2.25 0 0 1 4.75 3m11.655 9.473q-.098-.015-.195-.039t-.191-.056t-.185-.073t-.179-.089t-.169-.105t-.16-.119q-.077-.063-.148-.133q-.072-.069-.137-.145q-.064-.076-.122-.157t-.109-.167t-.093-.176t-.077-.184t-.061-.189t-.044-.195q-.017-.098-.026-.197t-.009-.199v-5q0-.111.011-.221t.032-.218t.054-.214t.074-.208q.043-.102.095-.2q.052-.097.113-.189t.132-.177t.148-.164t.164-.148q.085-.07.177-.132q.092-.061.189-.113q.098-.052.2-.095q.102-.042.208-.074t.214-.054t.218-.032T16.75 3t.221.011t.218.032q.108.022.214.054t.208.074q.102.043.2.095q.097.052.189.113t.177.132q.086.07.164.148t.148.164t.132.177q.061.092.113.189q.052.098.095.2q.042.102.074.208t.054.214t.032.218t.011.221v5q0 .24-.051.475t-.15.454t-.242.412t-.325.352M7 7.75h7.5m3.5 7v7m-2-5l2-2l2 2m-4 3l2 2l2-2");
}

</style>
