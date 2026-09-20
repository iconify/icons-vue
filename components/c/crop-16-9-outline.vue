<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bi2cr7m0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:crop-16-9-outline" /></template>
<style>
.bi2cr7m0e {
  fill: currentColor;
  d: path("M5.616 16q-.691 0-1.153-.462T4 14.385v-4.77q0-.69.463-1.152T5.616 8h12.769q.69 0 1.153.463T20 9.616v4.769q0 .69-.462 1.153T18.384 16zm0-1h12.769q.23 0 .423-.192t.192-.423v-4.77q0-.23-.192-.423T18.384 9H5.616q-.231 0-.424.192T5 9.616v4.769q0 .23.192.423t.423.192M5 15V9z");
}

</style>
