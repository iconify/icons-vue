<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j1gjjcckj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hockey-puck" /></template>
<style>
.j1gjjcckj {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.703 6.831Q2.749 8.047 2.75 9.999V14q0 2.329 2.867 3.85q2.639 1.4 6.383 1.4t6.383-1.4Q21.25 16.329 21.25 14V9.999q.002-1.951-2.953-3.168Q15.67 5.749 12 5.749T5.703 6.831M4.25 11.439q.125.114.27.225q.145.11.309.216q.163.106.345.207t.381.196t.413.184t.445.172t.473.158q.244.076.5.144t.524.128q.267.061.544.113t.563.097t.578.079q.292.036.59.063q.298.026.6.044t.606.027t.609.009t.609-.009t.606-.027t.6-.044t.59-.063q.293-.035.578-.079q.286-.045.563-.097t.544-.113q.268-.06.524-.128t.5-.144q.243-.076.473-.158q.23-.083.445-.172t.413-.184q.199-.095.381-.196t.345-.207q.164-.106.309-.216q.145-.111.27-.225V14q0 1.426-2.07 2.525Q15.371 17.75 12 17.75t-5.68-1.225Q4.25 15.426 4.25 14z");
}

</style>
