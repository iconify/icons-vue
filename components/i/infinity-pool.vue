<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="hvjmadiwx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:infinity-pool" /></template>
<style>
.hvjmadiwx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M7 16.5V6a2.25 2.25 0 0 0-4.5 0M14 14.3V6q0-.111-.011-.221t-.032-.218t-.054-.214t-.074-.208q-.043-.102-.095-.2q-.052-.097-.113-.189t-.132-.177q-.07-.086-.148-.164t-.164-.148T13 4.129q-.092-.061-.189-.113q-.098-.052-.2-.095q-.102-.042-.208-.074t-.214-.054t-.218-.032t-.221-.011t-.221.011t-.218.032q-.108.022-.214.054t-.208.074q-.102.043-.2.095q-.097.052-.189.113t-.177.132q-.086.07-.164.148t-.148.164q-.07.085-.132.177q-.061.092-.113.189q-.052.098-.095.2q-.042.102-.074.208t-.054.214t-.032.218T9.5 6M7 9.5h7M7 13h7M2.5 18q2.25-1.5 4.5 0t4.5 0q.119-.08.23-.142M2.5 21.25q2.25-1.5 4.5 0c1.5.75 3 .75 4 0M18 18c-1-1.5-3.5-1.5-3.5 0s2.5 1.5 3.5 0s3.5-1.5 3.5 0s-2.5 1.5-3.5 0");
}

</style>
