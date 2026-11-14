<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ps44jvb9u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:emergency-call-ringing" /></template>
<style>
.ps44jvb9u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M15.177 15.545q-.12.109-.258.194q-.137.085-.288.143q-.151.059-.31.088q-.159.03-.321.03C8 15.5 3.25 10.75 2.75 4.75q0-.086.008-.172t.026-.169q.016-.085.041-.167t.058-.162q.033-.079.074-.155t.088-.147q.048-.072.102-.138q.055-.067.116-.127q.06-.061.127-.116q.066-.054.138-.102q.071-.048.147-.088q.076-.041.155-.074q.08-.033.162-.058t.167-.041q.084-.017.169-.026T4.5 3H7l1.5 3.75l-1.75 1.5Q7.875 10.875 10.5 12l1.5-1.75l3.75 1.5v1.109M13.5 2.5a6.75 6.75 0 0 1 6.75 6.75m-6.75-3.5a3.5 3.5 0 0 1 3.5 3.5m1 5.25V18m0 3h.01");
}

</style>
