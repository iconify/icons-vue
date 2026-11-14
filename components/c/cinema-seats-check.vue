<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="atk-t-bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:cinema-seats-check" /></template>
<style>
.atk-t-bpy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5.75 2.5zA2.25 2.25 0 0 1 8 4.75v10.5a2.25 2.25 0 0 1-2.25 2.25a2.25 2.25 0 0 1-2.25-2.25V4.75A2.25 2.25 0 0 1 5.75 2.5m6.204 15H10.5q-.123 0-.245-.012t-.243-.036q-.12-.024-.238-.06t-.231-.082t-.221-.105t-.211-.126q-.102-.069-.197-.146q-.095-.078-.182-.165t-.165-.182t-.146-.197t-.126-.211t-.105-.221q-.047-.114-.082-.231t-.06-.238q-.024-.121-.036-.243T8 15t.012-.245t.036-.243q.024-.12.06-.238t.082-.231q.047-.113.105-.221q.058-.109.126-.211q.069-.102.146-.197q.078-.095.165-.182t.182-.165t.197-.146t.211-.126t.221-.105q.114-.047.231-.082t.238-.06q.121-.024.243-.036t.245-.012h5q.116 0 .232.011q.115.011.23.032q.114.021.225.053q.112.032.22.074q.108.043.212.095t.203.113q.098.061.191.132q.092.07.178.149t.163.164q.078.086.148.179t.13.192t.112.204t.092.212q.042.109.073.221t.051.226t.031.23M8 9h7.5M11 17.5V21m-3 0h5m1.75-3l2 2L21 15.75");
}

</style>
