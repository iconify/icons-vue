<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="t9sxlta2n"/><path class="gh7g_kbui"/><path class="lqx2c4v8h"/><path class="ie77fqdgv"/><path class="vtr9sm8sk"/><path class="ralk1_g3r"/><path class="gcnsrdrcw"/><path class="jdbbuibbk"/><path class="zzam3mbiu"/><path class="ugpnxl43w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bitcoin-broken" /></template>
<style>
.gcnsrdrcw {
  d: path("M11 6V7.5");
}

.gh7g_kbui {
  d: path("M9.75 7.5H12.75C13.9926 7.5 15 8.5074 15 9.75C15 10.9926 13.9926 12 12.75 12H9.75");
}

.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.ie77fqdgv {
  d: path("M9.75 7.5V16.5");
}

.jdbbuibbk {
  d: path("M13 6V7.5");
}

.lqx2c4v8h {
  d: path("M9.75 12H13.25C14.4926 12 15.5 13.0074 15.5 14.25C15.5 15.4926 14.4926 16.5 13.25 16.5H9.75");
}

.ralk1_g3r {
  d: path("M8.5 16.5H9.75");
}

.t9sxlta2n {
  d: path("M6.99975 3.33969C11.3457 0.830591 16.8783 1.93109 19.9332 5.91239C22.9882 9.89369 22.6192 15.5226 19.0708 19.0711C15.5223 22.6195 9.89345 22.9885 5.91215 19.9335C1.93085 16.8786 0.830347 11.346 3.33945 6.99999");
}

.ugpnxl43w {
  d: path("M13 16.5V18");
}

.vtr9sm8sk {
  d: path("M8.5 7.5H9.75");
}

.zzam3mbiu {
  d: path("M11 16.5V18");
}

</style>
