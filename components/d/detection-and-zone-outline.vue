<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jynwgjbkk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:detection-and-zone-outline" /></template>
<style>
.jynwgjbkk {
  fill: currentColor;
  d: path("M3 7V4.616q0-.691.463-1.153T4.615 3H7v1H4.616q-.231 0-.424.192T4 4.615V7zm4 14H4.616q-.691 0-1.153-.462T3 19.385V17h1v2.385q0 .23.192.423t.423.192H7zm10 0v-1h2.385q.23 0 .423-.192t.192-.424V17h1v2.385q0 .69-.462 1.152T19.385 21zm3-14V4.616q0-.231-.192-.424T19.385 4H17V3h2.385q.69 0 1.152.463T21 4.615V7zm-7.701 1.701q-.491-.492-.491-1.201t.491-1.201q.492-.491 1.201-.491t1.201.491q.491.491.491 1.201t-.491 1.201t-1.201.491t-1.201-.491m.117 8.684h-3l1.038-5.331L7.5 13.273V16.5h-1v-3.892l3.989-1.662q.644-.26.95-.353T12 10.5q.39 0 .725.208t.552.561l1 1.6q.63 1.012 1.743 1.745t2.48.848v1q-1.4-.096-2.809-.88q-1.408-.784-2.441-2.447z");
}

</style>
