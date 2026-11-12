<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="gcjr-xbce"/><path class="w6tva8xka"/><path class="k3hwyexex"/><path class="j4_t8hb-e"/><path class="tvpw9j7rv"/><path class="bdin2xoiv"/><path class="ffoe67b1y"/><path class="ql76lfbxa"/><path class="wvolq0b1y"/><path class="sev8m68qn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:calendar-linear" /></template>
<style>
.bdin2xoiv {
  stroke-linejoin: round;
  d: path("M17 16.7734H17.0001");
}

.ffoe67b1y {
  stroke-linejoin: round;
  d: path("M12 16.7734H12.0001");
}

.gcjr-xbce {
  d: path("M10 21.75H14C17.7712 21.75 19.6569 21.75 20.8284 20.5784C22 19.4069 22 17.5212 22 13.75V11.75C22 7.97876 22 6.09315 20.8284 4.92157C19.6569 3.75 17.7712 3.75 14 3.75H10C6.22876 3.75 4.34315 3.75 3.17157 4.92157C2 6.09315 2 7.97876 2 11.75V13.75C2 17.5212 2 19.4069 3.17157 20.5784C4.34315 21.75 6.22876 21.75 10 21.75Z");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.j4_t8hb-e {
  stroke-linejoin: round;
  d: path("M12 12.75H12.0001");
}

.k3hwyexex {
  stroke-linejoin: round;
  d: path("M17 12.75H17.0001");
}

.ql76lfbxa {
  stroke-linejoin: round;
  d: path("M7 16.7734H7.0001");
}

.sev8m68qn {
  d: path("M17 3.78496V2.25");
}

.tvpw9j7rv {
  stroke-linejoin: round;
  d: path("M7 12.75H7.0001");
}

.w6tva8xka {
  d: path("M2.03516 8.75H21.965");
}

.wvolq0b1y {
  d: path("M7 3.78496V2.25");
}

</style>
