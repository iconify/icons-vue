<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uk7k5qbmm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:hdr-on-select-outline" /></template>
<style>
.uk7k5qbmm {
  fill: currentColor;
  d: path("M14.825 10.825Q16 9.65 16 8t-1.175-2.825T12 4T9.175 5.175T8 8t1.175 2.825T12 12t2.825-1.175m-6.363.718Q7 10.086 7 8.005T8.457 4.46T11.995 3t3.544 1.457T17 7.996t-1.457 3.542T12.005 13T8.46 11.543m12.347 10.15v-2h-2v-.885h2v-2h.884v2h2v.884h-2v2zm-7.5 0v-5.385h2.884q.6 0 1.05.43t.45 1.07v.384q0 .46-.262.85q-.263.389-.791.589l.9 2.061h-.924l-.9-2h-1.523v2zm.884-2.885h2q.231 0 .424-.192q.192-.193.192-.424v-.384q0-.231-.192-.423q-.193-.193-.424-.193h-2zM.308 21.692v-5.384h.884v2h2.616v-2h.884v5.384h-.884v-2.5H1.192v2.5zm6.5 0v-5.384h2.884q.6 0 1.05.45t.45 1.05v2.384q0 .6-.45 1.05t-1.05.45zm.884-.884h2q.231 0 .424-.192q.192-.193.192-.424v-2.384q0-.231-.192-.423q-.193-.193-.424-.193h-2zM12 8");
}

</style>
