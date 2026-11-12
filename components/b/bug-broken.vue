<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="s-5fxtbvi"/><path class="hmbekl-gi"/><path class="v2njeqw1d"/><path class="p44zvobxz"/><path class="ql-kq8kab"/><path class="kka314x0o"/><path class="y-126g4df"/><path class="f9aqgrbmr"/><path class="r61ub7bmv"/><path class="a-4dztb1w"/><path class="ovmikkbyd"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:bug-broken" /></template>
<style>
.a-4dztb1w {
  d: path("M12 22V15");
}

.f9aqgrbmr {
  d: path("M17.7793 9.08789L20.4994 7.99984");
}

.hmbekl-gi {
  d: path("M16.5 8.27065V7.5C16.5 5.01472 14.4853 3 12 3C10.4398 3 9.06504 3.79401 8.25777 5M7.5 7.5V8.27065");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.kka314x0o {
  d: path("M9.70898 3.62569L6.99949 2");
}

.ovmikkbyd {
  d: path("M6.2207 9.08789L3.50067 7.99988");
}

.p44zvobxz {
  d: path("M5 14H2");
}

.ql-kq8kab {
  d: path("M14.291 3.62571L17.0005 2");
}

.r61ub7bmv {
  d: path("M6.19922 18.9202L3.49938 20.0001");
}

.s-5fxtbvi {
  d: path("M14 21.7101C13.3663 21.8987 12.695 22 12 22C8.13401 22 5 18.866 5 15V11.9375C5 9.76288 6.76288 8 8.9375 8H15.0625C17.2371 8 19 9.76288 19 11.9375V15C19 16.9073 18.2372 18.6364 17 19.899");
}

.v2njeqw1d {
  d: path("M19 14H22");
}

.y-126g4df {
  d: path("M17.8008 18.9202L20.5007 20.0001");
}

</style>
