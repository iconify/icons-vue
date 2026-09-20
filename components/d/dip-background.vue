<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="y0qo7tb1k"/><path class="djfo0tbse"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:dip-background" /></template>
<style>
.djfo0tbse {
  fill: var(--svg-color--fff, #fff);
  d: path("m19.433 10.012l-.049-.043l-.233-.214l-.606-.543l-.514-.465l-.087-.083l-.334.058l-3.19.33l-1.828-2.521a.34.34 0 0 0-.194-.121L5.9 5.343l-.825-.13l.446.586l.32.422H4l.848.795L9.94 11.81l-1.46 6.978l.068-.107l2.71-4.286l4.689-2.303a.8.8 0 0 0 .397-.344l.883-1.202H20zm-13.945-3.2h.8l1.688 2.332zm.931-.78l5.523.897l-1.746 4.242l-3.781-5.14zm3.244 9.857l.664-3.089l.451 1.29l-1.115 1.794zm1.585-2.139l-.581-1.745h4.12zm-.547-2.235l1.716-4.223l3.006 4.223zm5.294-.29l-1.188-1.63l2.444-.228l-1.26 1.862zm1.6-1.164l.31-.645l.752.645H17.59z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.y0qo7tb1k {
  fill: var(--svg-color--5081f4, #5081f4);
  d: path("M24 0H0v24h24z");
}

</style>
