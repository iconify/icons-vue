<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="cadln18ik"/><path class="wvolq0b1y"/><path class="sev8m68qn"/><path class="y0v0qnp7c"/><circle class="jx3h49bol"/><path class="d9v3nkbry"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-search-broken" /></template>
<style>
.cadln18ik {
  d: path("M22 13.75V11.75C22 7.97876 22 6.09315 20.8284 4.92157C19.6569 3.75 17.7712 3.75 14 3.75M14 21.75H10C6.22876 21.75 4.34315 21.75 3.17157 20.5784C2 19.4069 2 17.5212 2 13.75V11.75C2 7.97876 2 6.09315 3.17157 4.92157C4.34315 3.75 6.22876 3.75 10 3.75");
}

.d9v3nkbry {
  d: path("M20.1213 19.8713L21.9999 21.75");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jx3h49bol {
  cx: 18px;
  cy: 17.75px;
  r: 3px;
}

.sev8m68qn {
  d: path("M17 3.78496V2.25");
}

.wvolq0b1y {
  d: path("M7 3.78496V2.25");
}

.y0v0qnp7c {
  d: path("M21.965 8.75H16.6249H10.7499M5.87488 8.75H2.03485");
}

</style>
