<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="ehewotkqs"/><path class="hbv47lb9l"/><path class="fch9epbwt"/><path class="xfe_oobgk"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bluetooth-broken" /></template>
<style>
.ehewotkqs {
  d: path("M16.2633 4.6551C17.4211 5.47731 18 5.88842 18 6.45874C18 7.02907 17.4211 7.44017 16.2633 8.26238L11 12V5.22457C11 3.33816 11 2.39496 11.6047 2.08561C11.9666 1.90043 12.3885 2.02253 13 2.38554");
}

.fch9epbwt {
  d: path("M6 15.5L11 12");
}

.hbv47lb9l {
  d: path("M14.5253 20.5791L16.2633 19.3449C17.4211 18.5227 18 18.1116 18 17.5413C18 16.9709 17.4211 16.5598 16.2633 15.7376L11 12V18.7754C11 20.6618 11 21.605 11.6047 21.9144C12.2093 22.2238 12.9813 21.6755 14.5253 20.5791Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.xfe_oobgk {
  d: path("M6 8.5L11 12");
}

</style>
