<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="bomtt39jn"/><path class="z2kr6ybug"/><path class="k2g_6t_tj"/><path class="rcgoqzxit"/><path class="jdkg2b8su"/><path class="i2afqdhro"/><path class="li08e_y6g"/><path class="kdceb2bpp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:gamepad-no-charge-broken" /></template>
<style>
.bomtt39jn {
  d: path("M16.4042 17.2468C16.5877 17.8312 17.3584 19 18.9733 19C19.5033 19 19.9688 18.8741 20.3658 18.6842C21.6397 18.075 21.9701 16.5145 21.994 15.1026C22.0132 13.9681 21.9863 12.9362 21.9176 12M7.59582 17.2468C7.41231 17.8312 6.64158 19 5.02671 19C4.49667 19 4.03121 18.8741 3.63423 18.6842C2.3603 18.075 2.02992 16.5145 2.00604 15.1026C1.88749 8.09504 3.52645 5.00566 5.90915 4.16059C6.29009 4.02549 6.69838 4 7.10257 4H7.71504C8.59264 4 9.44862 4.27225 10.165 4.77922L10.6669 5.13443C11.0567 5.41029 11.5225 5.55844 12 5.55844C12.4776 5.55844 12.9434 5.41029 13.3332 5.13441L13.8351 4.77922C14.5514 4.27225 15.4074 4 16.2849 4H16.8974C17.3016 4 17.7099 4.02549 18.0908 4.16059C19.4281 4.63486 20.5311 5.81603 21.2206 8");
}

.i2afqdhro {
  stroke-linejoin: round;
  d: path("M16.75 11.75H16.7501");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.jdkg2b8su {
  stroke-linejoin: round;
  d: path("M15.25 10.25H15.2501");
}

.k2g_6t_tj {
  d: path("M10 17L14 21");
}

.kdceb2bpp {
  stroke-linejoin: round;
  d: path("M16.75 8.75H16.7501");
}

.li08e_y6g {
  stroke-linejoin: round;
  d: path("M18.25 10.25H18.2501");
}

.rcgoqzxit {
  d: path("M7.5 9V10.5M7.5 10.5V12M7.5 10.5L6 10.5M7.5 10.5L9 10.5");
}

.z2kr6ybug {
  d: path("M14 17L10 21");
}

</style>
