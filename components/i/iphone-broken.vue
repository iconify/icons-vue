<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ipq1z-bjh"><path class="l3jogvtxu"/><path class="erekrcbav"/><path class="iedl65bzf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:iphone-broken" /></template>
<style>
.erekrcbav {
  d: path("M15 19H9");
}

.iedl65bzf {
  d: path("M16.7484 2.37769L16.6643 2.50385C15.9082 3.63794 15.5302 4.205 14.978 4.54811C14.8682 4.61634 14.7541 4.6774 14.6365 4.73091C14.0447 5 13.3632 5 12.0002 5C10.6371 5 9.95564 5 9.36387 4.73091C9.2462 4.6774 9.13211 4.61634 9.02232 4.54811C8.47016 4.205 8.09213 3.63795 7.33606 2.50385L7.25195 2.37769");
}

.ipq1z-bjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.l3jogvtxu {
  d: path("M20 14C20 17.7712 20 19.6569 18.8284 20.8284C17.6569 22 15.7712 22 12 22C8.22876 22 6.34315 22 5.17157 20.8284C4 19.6569 4 17.7712 4 14V10C4 6.22876 4 4.34315 5.17157 3.17157C6.34315 2 8.22876 2 12 2C15.7712 2 17.6569 2 18.8284 3.17157C20 4.34315 20 6.22876 20 10");
}

</style>
