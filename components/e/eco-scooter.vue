<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r-n20ccqd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-sharp:eco-scooter" /></template>
<style>
.r-n20ccqd {
  fill: none;
  stroke: currentColor;
  stroke-linecap: square;
  stroke-miterlimit: 3.5;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 18A3.25 3.25 0 1 0 9 18a3.25 3.25 0 1 0-6.5 0Zm11.019-1.3q-.168.072-.324.167t-.296.213t-.262.253t-.223.289q-.101.152-.178.318q-.078.165-.13.341q-.053.175-.079.355Q12 18.817 12 19q0 .41.131.798t.379.715M5.75 14.75L8 3.5m-2.5 0h5M9 17.5h3.5m3 4c0-4.5 2-6.5 6-6.5c0 4.5-2 6.5-6 6.5Zm0 0l3.25-3.25");
}

</style>
