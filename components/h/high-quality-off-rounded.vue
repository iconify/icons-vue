<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="icn5lxb2h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:high-quality-off-rounded" /></template>
<style>
.icn5lxb2h {
  fill: currentColor;
  d: path("M7.5 12.692h2.616v1.558q0 .19.125.316q.126.126.317.126q.19 0 .316-.126T11 14.25v-3.058l-.885-.884v1.5H7.5V9.75q0-.19-.126-.316t-.316-.126t-.317.126t-.126.316v4.5q0 .19.126.316t.317.126t.316-.126t.126-.316zm9.885 2.035v-4.342q0-.444-.317-.761q-.316-.316-.76-.316h-2.231q-.425 0-.732.311t-.345.742l.885.866V10.5q0-.115.096-.212t.211-.096h2q.116 0 .212.096q.096.097.096.212v3.342zM21 6.616v9.782q0 .54-.497.745t-.876-.174L9.031 6.373q-.379-.379-.174-.876T9.602 5h9.783q.69 0 1.153.463T21 6.616M4.616 19q-.691 0-1.153-.462T3 17.384V6.616q0-.691.463-1.153T4.615 5h.193l9.692 9.692h-1.415L2.6 4.208q-.14-.14-.15-.344T2.6 3.5t.354-.16t.354.16l16.557 16.558q.14.14.153.341t-.153.366q-.16.16-.35.163q-.192.003-.357-.157L17.38 19z");
}

</style>
