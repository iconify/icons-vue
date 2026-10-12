<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><rect class="hmsjivy6h"/><path class="pb5exmvtp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="iconoven:dm-inbox" /></template>
<style>
.hmsjivy6h {
  width: 18.5px;
  height: 10px;
  x: 2.75px;
  y: 11.25px;
  rx: 3px;
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.pb5exmvtp {
  d: path("M2.75 15.5h4.5l1.5 2h6.5l1.5-2h4.5M19.64 3.23l-4.53 6.04q-.36.48-.71-.01l-1.3-1.77q-.35-.49-.93-.66l-3.09-.91q-.58-.17 0-.32l10.34-2.7q.58-.15.22.33");
}

</style>
