<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lcql4409p"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-7-5-outline-rounded" /></template>
<style>
.lcql4409p {
  fill: currentColor;
  d: path("M5.616 18q-.691 0-1.153-.462T4 16.384V7.616q0-.691.463-1.153T5.616 6h12.769q.69 0 1.153.463T20 7.616v8.769q0 .69-.462 1.153T18.384 18zm0-1h12.769q.23 0 .423-.192t.192-.424V7.616q0-.231-.192-.424T18.384 7H5.616q-.231 0-.424.192T5 7.616v8.769q0 .23.192.423t.423.192M5 17V7z");
}

</style>
