<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ulnmmdpxh"><path class="mme-5accm"/><path class="zattl4b9u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:car-inspection" /></template>
<style>
.mme-5accm {
  d: path("M4 13H2.5v-3A1.5 1.5 0 0 1 4 8.5h1.5l2.5-4h6l2.75 4H18a1.5 1.5 0 0 1 1.5 1.5v3H16m-4.5 0h-3");
}

.ulnmmdpxh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.zattl4b9u {
  d: path("M4 13a2.25 2.25 0 1 0 4.5 0A2.25 2.25 0 1 0 4 13Zm11.363 1.568q.152-.156.271-.338t.201-.384q.082-.201.123-.415Q16 13.218 16 13q0-.111-.011-.221t-.032-.218t-.054-.214t-.074-.208q-.043-.102-.095-.2q-.052-.097-.113-.189t-.132-.177q-.07-.086-.148-.164t-.164-.148t-.177-.132t-.189-.113t-.2-.095q-.102-.042-.208-.074t-.214-.054t-.218-.032t-.221-.011t-.221.011t-.218.032q-.108.022-.214.054t-.208.074t-.2.095q-.097.052-.189.113t-.177.132q-.086.07-.164.148t-.148.164t-.132.177t-.113.189t-.095.2q-.042.102-.074.208t-.054.214t-.032.218T11.5 13q0 .105.01.209q.009.104.029.207q.019.103.048.204t.067.198t.085.191t.103.183t.119.172t.134.16t.149.147t.162.133t.173.117t.184.101q.094.046.192.083t.199.065t.204.046t.207.026M14.75 18l2 2L21 15.75");
}

</style>
