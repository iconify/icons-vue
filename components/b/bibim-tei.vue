<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="mzoo_fb1k"/><path class="inz-7_bfi"/><path class="hz-6vmn0n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bibim-tei" /></template>
<style>
.hz-6vmn0n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.77 21.461c.671 1.665-.63 3.758-3.191 4.79s-5.413.613-6.084-1.052s1.093-3.945 3.654-4.977s4.95-.426 5.621 1.239m0 0l19.73-7.952");
}

.inz-7_bfi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.922 9.75a14.5 9.5 0 0 0-14.5 9.5a14.5 9.5 0 0 0 7.582 8.334a15 10 0 0 1-4.082-6.834a15 10 0 0 1 15-10a15 10 0 0 1 3.096.217a14.5 9.5 0 0 0-7.096-1.217");
}

.mzoo_fb1k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.355 20.816a16.5 10 0 0 1-16.434 9.434a16.5 10 0 0 1-16.414-9.274a16.5 16 0 0 0-.086 1.274a16.5 16 0 0 0 16.5 16a16.5 16 0 0 0 16.5-16a16.5 16 0 0 0-.066-1.434");
}

</style>
