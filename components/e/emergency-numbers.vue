<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="p03ms8b2x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:emergency-numbers" /></template>
<style>
.p03ms8b2x {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M19.929 11.661q.727-1.568 1.124-3.251T21.5 5q0-.123-.012-.245t-.036-.243q-.024-.12-.06-.238t-.082-.231t-.105-.221t-.126-.211q-.069-.102-.146-.197q-.078-.095-.165-.182t-.182-.165q-.095-.077-.197-.146t-.211-.126t-.221-.105q-.114-.047-.231-.082t-.238-.06q-.121-.024-.243-.036T19 2.5h-3.5L14 7l2 1.5q-.088.336-.198.666t-.242.651t-.284.634t-.325.614t-.366.591q-.192.29-.403.566t-.441.537q-.229.262-.474.508q-.246.245-.508.474q-.261.229-.537.441q-.276.211-.566.403t-.591.366t-.614.325q-.312.153-.634.284q-.321.132-.651.242T8.5 16L7 14l-4.5 1.5V19q0 .123.012.245t.036.243t.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126t.221.105q.114.047.231.082t.238.06t.243.036T5 21.5q.69-.02 1.376-.096q.687-.076 1.364-.207q.678-.131 1.343-.317t1.313-.425q.647-.239 1.274-.53q.626-.291 1.226-.632q.601-.341 1.172-.729q.57-.388 1.108-.821M18 14.5V18m0 3h.01");
}

</style>
