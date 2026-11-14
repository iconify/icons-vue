<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v82g8kzig"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dumbbell-minus" /></template>
<style>
.v82g8kzig {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M6.25 4.5zA1.75 1.75 0 0 1 8 6.25v8.5a1.75 1.75 0 0 1-1.75 1.75a1.75 1.75 0 0 1-1.75-1.75v-8.5A1.75 1.75 0 0 1 6.25 4.5m9.806 10.69Q16 14.974 16 14.75v-8.5q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147q.048-.072.102-.138q.055-.067.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041t.169-.026q.086-.008.172-.008t.172.008q.085.009.169.026q.085.016.167.041t.162.058t.155.074t.147.088t.138.102t.127.116t.116.127q.054.066.102.138q.048.071.088.147q.041.076.074.155q.033.08.058.162t.041.167q.017.084.026.169t.008.172v8.5q0 .224-.056.44M2.5 10.5h2m3.5 0h8m3.5 0h2M15 18h6");
}

</style>
