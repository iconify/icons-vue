<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gu2gsnbxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:defect-rate" /></template>
<style>
.gu2gsnbxl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 3L3 16M3 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0m11.496 7.363q-.006-.118-.024-.235t-.046-.232t-.068-.227t-.089-.22q-.05-.107-.11-.21q-.06-.102-.129-.198t-.147-.186t-.164-.17q-.086-.082-.18-.155q-.093-.073-.193-.137t-.205-.118t-.216-.098t-.224-.077t-.23-.055t-.234-.034T12 10.5q-.123 0-.245.012t-.243.036q-.12.024-.238.06t-.231.082q-.113.047-.221.105q-.109.058-.211.126q-.102.069-.197.146q-.095.078-.182.165t-.165.182t-.146.197t-.126.211t-.105.221q-.047.114-.082.231t-.06.238q-.024.121-.036.243T9.5 13t.012.245t.036.243q.024.12.06.238t.082.231q.047.113.105.221q.058.109.126.211q.069.102.146.197q.078.095.165.182t.182.165t.197.146t.211.126t.221.105q.114.047.231.082t.238.06q.121.024.243.036T12 15.5q.38 0 .742-.113m2.758.113l5 5m0-5l-5 5");
}

</style>
