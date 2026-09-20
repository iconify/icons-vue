<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c100fbcnl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:fit-page-height-rounded" /></template>
<style>
.c100fbcnl {
  fill: currentColor;
  d: path("M6.616 21q-.691 0-1.153-.462T5 19.385V4.615q0-.69.463-1.152T6.616 3h10.769q.69 0 1.153.463T19 4.616v14.769q0 .69-.462 1.153T17.384 21zM10.43 8.808h3.138q.273 0 .37-.252t-.097-.445l-1.276-1.277q-.243-.242-.566-.242t-.565.242l-1.277 1.277q-.192.193-.096.445t.369.252m2.135 8.358l1.276-1.277q.193-.193.097-.445q-.097-.252-.37-.252H10.43q-.273 0-.37.252q-.095.252.097.444l1.277 1.278q.242.242.565.242t.566-.243");
}

</style>
