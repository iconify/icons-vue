<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kexs9w4ka"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:alarm-pause-outline-rounded" /></template>
<style>
.kexs9w4ka {
  fill: currentColor;
  d: path("M10.665 16.357q.143-.143.143-.357V9.994q0-.213-.143-.353q-.144-.141-.357-.141t-.357.143t-.143.357v6q0 .214.143.357t.357.143t.357-.143m3.384 0q.143-.143.143-.357V9.994q0-.213-.143-.353q-.143-.141-.357-.141t-.356.143t-.144.357v6q0 .214.144.357t.356.143t.357-.143m-5.167 4.017q-1.455-.626-2.542-1.713t-1.714-2.543T4 13t.626-3.118T6.34 7.34t2.542-1.714T12 5t3.118.626T17.66 7.34t1.714 2.542T20 13t-.626 3.118t-1.714 2.543t-2.542 1.713T12 21t-3.118-.626M2.78 7.262q-.16-.16-.16-.354t.16-.354L5.554 3.78q.14-.14.344-.15t.364.15t.16.353q0 .195-.16.354L3.489 7.261q-.141.141-.345.15t-.363-.15m18.438 0q-.16.16-.353.16q-.195 0-.354-.16L17.738 4.49q-.14-.141-.15-.345t.15-.363t.354-.16t.354.16l2.773 2.773q.14.14.15.344t-.15.364M12 20q2.906 0 4.953-2.047T19 13t-2.047-4.953T12 6T7.047 8.047T5 13t2.047 4.953T12 20");
}

</style>
