<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jbm2l9b0u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:defect-rate" /></template>
<style>
.jbm2l9b0u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15 3L3 16M3 5.5a2.5 2.5 0 1 0 5 0a2.5 2.5 0 1 0-5 0Zm11.464 7.076q-.019-.108-.047-.214q-.028-.105-.065-.208t-.083-.203t-.1-.194t-.117-.185t-.133-.174t-.147-.162q-.077-.077-.161-.148t-.173-.133t-.185-.118q-.094-.055-.194-.101q-.099-.047-.202-.084q-.102-.038-.208-.066t-.214-.048q-.107-.019-.216-.028q-.11-.01-.219-.01q-.123 0-.245.012t-.243.036q-.12.024-.238.06t-.231.082q-.113.047-.221.105q-.109.058-.211.126q-.102.069-.197.146q-.095.078-.182.165t-.165.182t-.146.197t-.126.211t-.105.221q-.047.114-.082.231t-.06.238q-.024.121-.036.243T9.5 13q0 .11.01.22q.009.109.029.218q.019.108.048.214q.028.107.066.21t.085.203t.103.195t.119.185t.134.173t.15.161q.078.078.163.148t.176.132q.09.063.186.117t.196.1t.204.082t.211.064t.215.045m3.905.033l5 5m0-5l-5 5");
}

</style>
