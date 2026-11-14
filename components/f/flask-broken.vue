<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="hntgybcog"><path class="rocca9t6a"/><path class="q9kam2ahf"/><path class="lymkt6hgt"/><path class="osur0_jqd"/><path class="mce_0k4my"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="solar:flask-broken" /></template>
<style>
.hntgybcog {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
}

.lymkt6hgt {
  d: path("M15.1402 22H16.8002C19.8002 22 21.2002 18.8 19.6002 16.4L17.2002 12.8C15.6002 10.4 14.2002 9.00005 14.2002 7.20015V4.80005");
}

.mce_0k4my {
  d: path("M10.1992 18.5H10.1993");
}

.osur0_jqd {
  d: path("M5.33398 15C7.80068 14.1 10.2007 14.1 12.0007 15C13.8007 15.9 16.2007 15.9 18.6674 15");
}

.q9kam2ahf {
  d: path("M9.79986 4.80005V7.20015C9.79986 9.00005 8.39986 10.4 6.79986 12.8L4.39986 16.4C2.79986 18.8 4.19986 22 7.19986 22H11.7399");
}

.rocca9t6a {
  d: path("M8.19922 3.4C8.19922 2.74 8.19922 2.4101 8.40422 2.205C8.60932 2 8.93922 2 9.59922 2H14.3992C15.0592 2 15.3891 2 15.5942 2.205C15.7992 2.4101 15.7992 2.74 15.7992 3.4C15.7992 4.06 15.7992 4.3899 15.5942 4.595C15.3891 4.8 15.0592 4.8 14.3992 4.8H9.59922C8.93922 4.8 8.60932 4.8 8.40422 4.595C8.19922 4.3899 8.19922 4.06 8.19922 3.4Z");
}

</style>
