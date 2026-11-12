<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="plmy2zvgw"/><path class="s5eh35bzd"/><path class="hixqu8e0n"/><path class="mioco9dwm"/><path class="g4enlftii"/><path class="ymq-tib4j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-wave-linear" /></template>
<style>
.g4enlftii {
  d: path("M19 5C19 5 21 7.1 21 12C21 16.9 19 19 19 19");
}

.hixqu8e0n {
  d: path("M8 12L3 15.5");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.mioco9dwm {
  d: path("M8 12L3 8.5");
}

.plmy2zvgw {
  d: path("M13.2633 8.26238L8 12V5.22457C8 3.33816 8 2.39496 8.60465 2.08561C9.2093 1.77625 9.98131 2.32448 11.5253 3.42093L13.2633 4.6551C14.4211 5.47731 15 5.88842 15 6.45874C15 7.02907 14.4211 7.44017 13.2633 8.26238Z");
}

.s5eh35bzd {
  d: path("M13.2633 19.3449L11.5253 20.5791C9.98131 21.6755 9.2093 22.2238 8.60465 21.9144C8 21.605 8 20.6618 8 18.7754V12L13.2633 15.7376C14.4211 16.5598 15 16.9709 15 17.5413C15 18.1116 14.4211 18.5227 13.2633 19.3449Z");
}

.ymq-tib4j {
  d: path("M17 8C17 8 18 9.9 18 12C18 14.1 17 16 17 16");
}

</style>
