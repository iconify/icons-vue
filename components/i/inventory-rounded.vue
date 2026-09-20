<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="f__y8ka9r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:inventory-rounded" /></template>
<style>
.f__y8ka9r {
  fill: currentColor;
  d: path("m15.5 17.798l5.335-5.334q.14-.141.344-.15t.363.15t.16.353t-.16.354l-5.477 5.477q-.242.243-.565.243t-.565-.243l-2.639-2.639q-.14-.14-.15-.344t.15-.363t.354-.16t.354.16zM5.616 20q-.672 0-1.144-.472T4 18.385V5.615q0-.67.472-1.143Q4.944 4 5.616 4h4.636q.14-.586.623-.985q.483-.4 1.125-.4q.654 0 1.134.4q.48.398.62.985h4.63q.672 0 1.144.472T20 5.616V9.5q0 .214-.143.357T19.5 10t-.357-.143T19 9.5V5.616q0-.231-.192-.424T18.384 5H16v1.423q0 .348-.23.578t-.578.23H8.808q-.348 0-.578-.23T8 6.423V5H5.616q-.231 0-.424.192T5 5.616v12.769q0 .23.192.423t.423.192H10.5q.214 0 .357.143T11 19.5t-.143.357T10.5 20zm6.962-14.999q.23-.23.23-.578t-.23-.578t-.578-.23t-.578.23t-.23.578t.23.578t.578.23t.578-.23");
}

</style>
