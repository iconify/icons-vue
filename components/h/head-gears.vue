<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="ocyf5ip6z"/><path class="l28m8vtld"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:head-gears" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l28m8vtld {
  d: path("M9.633 6.701za1.15 1.15 0 0 0 .972.403a.502.502 0 0 1 .541.541a1.15 1.15 0 0 0 .403.972a.502.502 0 0 1 0 .766a1.15 1.15 0 0 0-.403.972a.502.502 0 0 1-.541.541a1.15 1.15 0 0 0-.972.403a.502.502 0 0 1-.766 0a1.15 1.15 0 0 0-.972-.403a.502.502 0 0 1-.541-.541a1.15 1.15 0 0 0-.403-.972a.502.502 0 0 1 0-.766a1.15 1.15 0 0 0 .403-.972a.502.502 0 0 1 .541-.541a1.15 1.15 0 0 0 .972-.403a.502.502 0 0 1 .766 0m5.442 5.248za1.03 1.03 0 0 0 .88.424a.402.402 0 0 1 .406.509a1.03 1.03 0 0 0 .217.951a.402.402 0 0 1-.145.635a1.03 1.03 0 0 0-.609.763a.402.402 0 0 1-.586.283a1.03 1.03 0 0 0-.976 0a.402.402 0 0 1-.586-.283a1.03 1.03 0 0 0-.609-.763a.402.402 0 0 1-.145-.635a1.03 1.03 0 0 0 .217-.951a.402.402 0 0 1 .406-.509a1.03 1.03 0 0 0 .88-.424a.402.402 0 0 1 .65 0");
}

.ocyf5ip6z {
  d: path("M8 21.5v-4c-2.5-1.75-3.5-4.25-3.5-7C4.5 6.25 7.75 3 12 3c4 0 7 2.75 7 6.75l1.5 3.5c.25.5-.1 1-.75 1H19v2.25c0 1.1-.9 2-2 2h-2v3");
}

</style>
