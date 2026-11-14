<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ir67rebvw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:discount-bundle-save" /></template>
<style>
.ir67rebvw {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M5 5h3.75a1.75 1.75 0 0 1 1.75 1.75v8a1.75 1.75 0 0 1-1.75 1.75H5a1.75 1.75 0 0 1-1.75-1.75v-8A1.75 1.75 0 0 1 5 5m8.25 8.975V6.75q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147q.048-.072.102-.138q.055-.067.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041t.169-.026Q14.914 5 15 5h3.75q.086 0 .172.008t.169.026q.085.016.167.041t.162.058t.155.074t.147.088t.138.102t.127.116t.116.127q.054.066.102.138q.048.071.088.147q.041.076.074.155q.033.08.058.162t.041.167q.017.084.026.169t.008.172v4.675M2 10.75h20M6.75 5v2.5m10-2.5v2.5m.51 6.75h2.99a1.5 1.5 0 0 1 1.5 1.5v4.5a1.5 1.5 0 0 1-1.5 1.5h-2.99a1.5 1.5 0 0 1-1.209-.613l-1.65-2.25a1.5 1.5 0 0 1 0-1.774l1.65-2.25a1.5 1.5 0 0 1 1.209-.613M16.75 18h.01");
}

</style>
