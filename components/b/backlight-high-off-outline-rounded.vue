<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rov5r50yd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:backlight-high-off-outline-rounded" /></template>
<style>
.rov5r50yd {
  fill: currentColor;
  d: path("M15.573 17H8.5q-.413 0-.707-.293T7.5 16t.293-.707T8.5 15h5.073L3.094 4.521q-.146-.146-.155-.347t.155-.366t.357-.166t.357.166l16.384 16.384q.147.147.156.345t-.156.363t-.356.166t-.357-.166zM2.116 14.5q-.214 0-.357-.143T1.616 14t.143-.357t.357-.143H4.5q.214 0 .357.143T5 14t-.143.357t-.357.143zm9.527-7.643Q11.5 6.714 11.5 6.5V3.116q0-.214.143-.357T12 2.616t.357.143t.143.357V6.5q0 .214-.143.357T12 7t-.357-.143m5.268 2.174q-.14-.14-.13-.354t.15-.354l1.732-1.694q.14-.14.351-.15t.357.15q.146.146.137.354q-.01.208-.156.354L17.619 9.03q-.14.14-.353.15q-.214.01-.354-.15M19.5 14.5q-.213 0-.357-.143T19 14t.143-.357t.357-.143h2.385q.213 0 .356.143t.144.357t-.144.357t-.356.143z");
}

</style>
