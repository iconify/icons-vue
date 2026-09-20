<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xnlap7bfj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:detection-and-zone-off-outline" /></template>
<style>
.xnlap7bfj {
  fill: currentColor;
  d: path("m21.11 22.58l-8.121-8.126l-.574 2.93h-3l1.039-5.33L7.5 13.273V16.5h-1v-3.892l3.285-1.352l-7.898-7.898l.713-.714l19.223 19.223zM4.616 21q-.691 0-1.153-.462T3 19.385V17h1v2.385q0 .23.192.423t.423.192H7v1zM20 7V4.616q0-.231-.192-.424T19.385 4H17V3h2.385q.69 0 1.152.463T21 4.615V7zM3 7V4.616q0-.349.115-.644q.114-.295.306-.513l.733.739q-.058.096-.106.202T4 4.621V7zm14 14v-1h2.379q.115 0 .221-.048t.164-.144l.732.727q-.192.217-.478.341t-.633.124zM6.767 4l-1-1H7v1zM21 18.233l-1-1V17h1zm-7.5-9.04q-.71 0-1.201-.492T11.808 7.5t.491-1.201t1.201-.491t1.201.491t.491 1.201t-.491 1.201q-.492.491-1.201.491");
}

</style>
