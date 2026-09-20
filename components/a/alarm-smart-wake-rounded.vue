<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="idkz8xpip"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:alarm-smart-wake-rounded" /></template>
<style>
.idkz8xpip {
  fill: currentColor;
  d: path("M8.77 13.52q.21-.21.21-.52t-.21-.52t-.52-.21t-.52.21t-.21.52t.21.52t.52.21t.52-.21m3.75 0q.21-.21.21-.52t-.21-.52t-.52-.21t-.52.21t-.21.52t.21.52t.52.21t.52-.21m3.75 0q.21-.21.21-.52t-.21-.52t-.52-.21t-.52.21t-.21.52t.21.52t.52.21t.52-.21m-7.388 6.854q-1.455-.626-2.542-1.713t-1.714-2.543T4 13t.626-3.118T6.34 7.34t2.542-1.714T12 5t3.118.626T17.66 7.34t1.714 2.542T20 13t-.626 3.118t-1.714 2.543t-2.542 1.713T12 21t-3.118-.626M2.78 7.262q-.16-.16-.16-.354t.16-.354L5.554 3.78q.14-.14.344-.15t.364.15t.16.353q0 .195-.16.354L3.489 7.261q-.141.141-.345.15t-.363-.15m18.438 0q-.16.16-.353.16q-.195 0-.354-.16L17.738 4.49q-.14-.141-.15-.345t.15-.363t.354-.16t.354.16l2.773 2.773q.14.14.15.344t-.15.364");
}

</style>
