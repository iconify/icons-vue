<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="epyenkkad"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:alarm-rounded" /></template>
<style>
.epyenkkad {
  fill: currentColor;
  d: path("M12.5 12.792V8.5q0-.213-.143-.357T12 8t-.357.143t-.143.357v4.379q0 .162.056.3q.056.14.186.271l3.05 3.05q.14.14.345.15t.363-.15t.16-.354t-.16-.354zm-3.618 7.582q-1.455-.626-2.542-1.713t-1.714-2.543T4 13t.626-3.118T6.34 7.34t2.542-1.714T12 5t3.118.626T17.66 7.34t1.714 2.542T20 13t-.626 3.118t-1.714 2.543t-2.542 1.713T12 21t-3.118-.626M2.78 7.262q-.16-.16-.16-.354t.16-.354L5.554 3.78q.14-.14.344-.15t.364.15t.16.353q0 .195-.16.354L3.489 7.261q-.141.141-.345.15t-.363-.15m18.438 0q-.16.16-.353.16q-.195 0-.354-.16L17.738 4.49q-.14-.141-.15-.345t.15-.363t.354-.16t.354.16l2.773 2.773q.14.14.15.344t-.15.364");
}

</style>
