<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kmhi5jbgp"/><path class="kvo_b0bqf"/><circle class="s8wm1bk8w"/><circle class="g0a5jpbkq"/><path class="c4ce4665m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:heads-up" /></template>
<style>
.c4ce4665m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.374 32.327s1.398.858 1.266 2.553s-1.328 2.507-1.328 2.507m-2.995-4.203s-.642 1.642.016 2.62c.809 1.24 1.655 1.617 1.655 1.617M3.5 27.725h41m-39.375 0s.457-13.192 7.75-15.645s10.227-1.314 14.027-.876s10.053.23 13.088 5.782c3.64 6.657 1.423 10.74 1.423 10.74");
}

.g0a5jpbkq {
  cx: 33.962px;
  cy: 34.169px;
  r: 0.75px;
  fill: currentColor;
}

.kmhi5jbgp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.059 37.404s2.101-5.32 6.25-5.08c4.15.239 4.922 2.792 4.922 2.792s-.798 2.128-4.629 2.261s-6.543.027-6.543.027m-10.118 0s-2.101-5.32-6.25-5.08c-4.15.239-4.922 2.792-4.922 2.792s.798 2.128 4.628 2.261s6.544.027 6.544.027");
}

.kvo_b0bqf {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M16.13 33.605s.707 1.219.042 2.376s-1.304 1.454-1.304 1.454m-1.638-5.112s-1.58 1.044-1.46 2.557s1.334 2.52 1.334 2.52");
}

.s8wm1bk8w {
  cx: 13.865px;
  cy: 34.363px;
  r: 0.75px;
  fill: currentColor;
}

</style>
