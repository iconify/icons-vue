<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="hv0btrbhp"/><path class="s3qjqub9e"/><path class="k1c91c4lo"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:delivery-redelivery" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.hv0btrbhp {
  d: path("m11.245 18.064l-.4.22q-.194.107-.409.162t-.436.056t-.436-.056q-.215-.055-.409-.162l-5.5-3.035q-.102-.056-.196-.126q-.094-.069-.178-.151t-.156-.173t-.132-.192t-.105-.209q-.045-.107-.076-.22t-.046-.228q-.016-.116-.016-.233V7.283q0-.117.016-.233q.015-.115.046-.228t.076-.22t.105-.209q.06-.1.132-.192t.156-.173q.084-.082.178-.151q.094-.07.196-.126l5.5-3.035q.194-.107.409-.162T10 2.498t.436.056q.215.055.409.162l5.5 3.035q.102.056.196.126q.094.069.178.151t.156.173t.132.192q.059.101.105.209q.045.107.076.22t.046.228t.016.233v2.639");
}

.k1c91c4lo {
  d: path("m16.25 12.5l1.5 1.5l-1.5 1.5");
}

.s3qjqub9e {
  d: path("M2.75 6.25L10 10.5l7.25-4.25M10 10.5v8.25m11.5-1A3.75 3.75 0 1 1 17.75 14");
}

</style>
