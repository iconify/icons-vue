<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="wimbc893y"/><path class="wvolq0b1y"/><path class="sev8m68qn"/><path class="y0v0qnp7c"/><path class="xcs4aye_u"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-add-broken" /></template>
<style>
.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.sev8m68qn {
  d: path("M17 3.78496V2.25");
}

.wimbc893y {
  d: path("M14 21.75H10C6.22876 21.75 4.34315 21.75 3.17157 20.5784C2 19.4069 2 17.5212 2 13.75V11.75C2 7.97876 2 6.09315 3.17157 4.92157C4.34315 3.75 6.22876 3.75 10 3.75H14C17.7712 3.75 19.6569 3.75 20.8284 4.92157C22 6.09315 22 7.97876 22 11.75V13.75C22 17.5212 22 19.4069 20.8284 20.5784C20.1752 21.2316 19.3001 21.5206 18 21.6485");
}

.wvolq0b1y {
  d: path("M7 3.78496V2.25");
}

.xcs4aye_u {
  d: path("M18 15.75H16M16 15.75L14 15.75M16 15.75L16 13.75M16 15.75L16 17.75");
}

.y0v0qnp7c {
  d: path("M21.965 8.75H16.6249H10.7499M5.87488 8.75H2.03485");
}

</style>
