<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="eh1lsdyrd"/><path class="ooj7qtbpk"/><defs><path id="SVGTEMn9bNR" class="oie7okb_w"/></defs><use href="#SVGTEMn9bNR" class="j71m3fb1u"/><clipPath id="SVGVxyDHc0A"><use href="#SVGTEMn9bNR"/></clipPath><path clip-path="url(#SVGVxyDHc0A)" class="xn39njbns"/><circle class="kg-e92blw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:house" /></template>
<style>
.eh1lsdyrd {
  fill: var(--svg-color--855c52, #855c52);
  d: path("M33.14 75.07h31.27V128H33.14z");
}

.j71m3fb1u {
  fill: var(--svg-color--fcc21b, #fcc21b);
}

.kg-e92blw {
  cx: 42.86px;
  cy: 107.7px;
  r: 3.6px;
  fill: var(--svg-color--fff, #fff);
}

.oie7okb_w {
  d: path("M113.78 56.88L68.02 15.23c-2.21-2.01-5.83-2.01-8.04 0L14.21 56.88c-2.21 2.02-4.02 6.11-4.02 9.1v56.59c0 2.99 2.45 5.44 5.43 5.44h21.01V90.68c0-2.28 1.86-4.14 4.13-4.14h16.56c2.27 0 4.14 1.86 4.14 4.14V128h50.91c2.99 0 5.44-2.44 5.44-5.44V65.97c0-2.98-1.81-7.08-4.03-9.09m-26.25 44.86h-5.91c-2.76 0-5.03-2.26-5.03-5.03v-5.05h10.94zm0-14.88H76.59v-6.77c0-2.76 2.27-5.03 5.03-5.03h5.91zm15.73 9.85c0 2.76-2.26 5.03-5.03 5.03h-5.91V91.66h10.94zm0-9.85H92.33V75.07h5.91a5.04 5.04 0 0 1 5.03 5.03v6.76z");
}

.ooj7qtbpk {
  fill: var(--svg-color--fff, #fff);
  d: path("M74.01 72.27h32.24v32.59H74.01z");
}

.xn39njbns {
  fill: var(--svg-color--ed6c30, #ed6c30);
  d: path("m64.72 26.29l53.98 49.99l1.26.01l.57-18.25L64.72 6.36L7.6 58.04L7.24 75.1l3.5.03z");
}

</style>
