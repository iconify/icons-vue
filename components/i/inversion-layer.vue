<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="domt6obwp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:inversion-layer" /></template>
<style>
.domt6obwp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 4.5h19M14.054 14H5q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082q-.113-.047-.221-.105q-.109-.058-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182q-.077-.095-.146-.197t-.126-.211q-.058-.108-.105-.221q-.047-.114-.082-.231t-.06-.238q-.024-.121-.036-.243T2.5 11.5t.012-.245t.036-.243q.024-.12.06-.238t.082-.231q.047-.113.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165t.197-.146t.211-.126t.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036T5 9h14q.119 0 .238.011q.118.012.235.034t.231.056t.225.078t.217.099t.206.119t.194.138t.179.156q.087.082.165.172t.147.187t.128.2t.109.212t.089.221t.067.228t.045.234t.022.237M2.5 18.5h10.8m3.45-1v-2.75a1.75 1.75 0 0 1 3.5 0v2.75a2.5 2.5 0 1 1-3.5 0");
}

</style>
