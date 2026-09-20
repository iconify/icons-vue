<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wq1-vvbac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:luggage-outline-sharp" /></template>
<style>
.wq1-vvbac {
  fill: currentColor;
  d: path("M7.462 20H5.845V6.385h3.77V3h4.769v3.385h3.769V20h-1.616v.23q0 .31-.23.54t-.539.23t-.54-.23t-.229-.54V20H9v.23q0 .31-.23.54t-.54.23t-.539-.23t-.23-.54zm-.616-1h10.308V7.385H6.846zm2.77-1.77h1V9.155h-1zm3.768 0h1V9.155h-1zM10.616 6.385h2.769V4h-2.77zM12 13.192");
}

</style>
