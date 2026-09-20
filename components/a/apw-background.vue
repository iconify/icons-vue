<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="decy2cacw"/><path clip-rule="evenodd" class="vs6b_2bpl"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:apw-background" /></template>
<style>
.decy2cacw {
  fill: var(--svg-color--fec093, #fec093);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vs6b_2bpl {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M11.765 19.53v-1.064l-2.127-1.76H6.16l1.195-1.883l-1.002-.828v-3.99l5.412-4.236V4.471a7.53 7.53 0 0 0 0 15.049zM19.529 12a7.53 7.53 0 0 1-7.294 7.53v-1.083l1.742-1.741h3.849l-1.097-1.859l.918-.602v-4.24l-5.412-4.236V4.471A7.53 7.53 0 0 1 19.53 12m.47 0a8 8 0 1 1-16 0a8 8 0 0 1 16 0M7.016 16.235l.706-1.11l1.346 1.11H7.012zm6.297.47l-1.078 1.083v-1.082h1.083zm3.685-.47h-4.763V14.24l-2.927-2.292l2.683-4.202zm-4.989-9.393l-3.073 4.815l-1.971-1.54L12 6.18l5.026 3.939l-2.132 1.623l-2.885-4.894zM6.824 13.77v-3.167l4.94 3.864v3.388zm8.31-1.628l2.043-1.553v3.403l-.688.451z");
}

</style>
