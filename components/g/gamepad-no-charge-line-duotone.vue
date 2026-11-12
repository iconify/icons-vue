<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="y2dvpuw2h"/><path class="z2kr6ybug"/><path class="k2g_6t_tj"/><path class="macts57ml"/><path class="ci9s2pb7v"/><path class="childjbrq"/><path class="yl5rcw6_j"/><path class="awhm0p1km"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gamepad-no-charge-line-duotone" /></template>
<style>
.awhm0p1km {
  stroke-linejoin: round;
  d: path("M16.75 8.75H16.7501");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.childjbrq {
  stroke-linejoin: round;
  d: path("M16.75 11.75H16.7501");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ci9s2pb7v {
  stroke-linejoin: round;
  d: path("M15.25 10.25H15.2501");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.k2g_6t_tj {
  d: path("M10 17L14 21");
}

.macts57ml {
  d: path("M7.5 9V10.5M7.5 10.5V12M7.5 10.5L6 10.5M7.5 10.5L9 10.5");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.y2dvpuw2h {
  d: path("M16.4042 17.2468C16.5877 17.8312 17.3584 19 18.9733 19C19.5033 19 19.9688 18.8741 20.3658 18.6842C21.6397 18.075 21.9701 16.5145 21.994 15.1026C22.1125 8.09503 20.4735 5.00566 18.0908 4.16059C17.7099 4.02549 17.3016 4 16.8974 4H16.2849C15.4074 4 14.5514 4.27225 13.8351 4.77922L13.3332 5.13441C12.9434 5.41029 12.4776 5.55844 12 5.55844C11.5225 5.55844 11.0567 5.41029 10.6669 5.13443L10.165 4.77922C9.44862 4.27225 8.59264 4 7.71504 4H7.10257C6.69838 4 6.29009 4.02549 5.90915 4.16059C3.52645 5.00566 1.88749 8.09504 2.00604 15.1026C2.02992 16.5145 2.3603 18.075 3.63423 18.6842C4.03121 18.8741 4.49667 19 5.02671 19C6.64158 19 7.41231 17.8312 7.59582 17.2468");
}

.yl5rcw6_j {
  stroke-linejoin: round;
  d: path("M18.25 10.25H18.2501");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.z2kr6ybug {
  d: path("M14 17L10 21");
}

</style>
