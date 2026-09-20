<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j5lp--9do"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-7-5-rounded" /></template>
<style>
.j5lp--9do {
  fill: currentColor;
  d: path("M5.616 18q-.691 0-1.153-.462T4 16.384V7.616q0-.691.463-1.153T5.616 6h12.769q.69 0 1.153.463T20 7.616v8.769q0 .69-.462 1.153T18.384 18z");
}

</style>
