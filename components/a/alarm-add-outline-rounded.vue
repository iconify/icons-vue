<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xa-230bpr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:alarm-add-outline-rounded" /></template>
<style>
.xa-230bpr {
  fill: currentColor;
  d: path("M11.5 13.5V16q0 .213.144.356t.357.144t.356-.144T12.5 16v-2.5H15q.213 0 .356-.144t.144-.357t-.144-.356T15 12.5h-2.5V10q0-.213-.144-.356t-.357-.144t-.356.144T11.5 10v2.5H9q-.213 0-.356.144t-.144.357t.144.356T9 13.5zm-2.618 6.874q-1.455-.626-2.542-1.713t-1.714-2.542T4 13.001t.626-3.12T6.34 7.34t2.54-1.714T12 5t3.12.626t2.54 1.714t1.713 2.54T20 13t-.626 3.12t-1.714 2.542t-2.54 1.713T12 21t-3.12-.626M2.78 7.262q-.16-.16-.16-.354t.16-.354L5.554 3.78q.14-.14.344-.15t.364.15t.16.353q0 .195-.16.354L3.489 7.261q-.141.141-.345.15t-.363-.15m18.438 0q-.16.16-.353.16q-.195 0-.354-.16L17.738 4.49q-.14-.141-.15-.345t.15-.363t.354-.16t.354.16l2.773 2.773q.14.14.15.344t-.15.364M12 20q2.906 0 4.953-2.047T19 13t-2.047-4.953T12 6T7.047 8.047T5 13t2.047 4.953T12 20");
}

</style>
