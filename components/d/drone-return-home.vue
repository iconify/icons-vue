<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t-ef9sbuv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:drone-return-home" /></template>
<style>
.t-ef9sbuv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.75a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m10.5 0a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0M2.5 15.25a2.25 2.25 0 1 0 4.5 0a2.25 2.25 0 1 0-4.5 0m14.606-1.272q-.078-.113-.168-.216q-.09-.102-.192-.193q-.102-.09-.214-.168q-.113-.078-.233-.142t-.249-.112q-.127-.048-.26-.081q-.132-.033-.268-.049Q15.387 13 15.25 13q-.111 0-.221.011t-.218.032t-.214.054t-.208.074q-.102.043-.2.095q-.097.052-.189.113t-.177.132q-.086.07-.164.148t-.148.164t-.132.177t-.113.189t-.095.2q-.042.102-.074.208t-.054.214t-.032.218t-.011.221q0 .253.056.499t.165.474t.266.425t.354.356M8 10a2 2 0 1 0 4 0a2 2 0 1 0-4 0M6.25 6.25L8.5 8.5m5.25-2.25L11.5 8.5m-5.25 5.25L8.5 11.5m5.25 2.25L11.5 11.5M16 22v-3.25L19 16l3 2.75V22Z");
}

</style>
