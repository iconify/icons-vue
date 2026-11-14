<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nzbzs4u8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:event-invite" /></template>
<style>
.nzbzs4u8d {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m20.584 10.376l-2.334 1.556V4q0-2.25-2.25-2.25H8Q5.75 1.75 5.75 4v7.932l-2.334-1.556Q3.227 10.25 3 10.25q-.084 0-.165.018q-.082.019-.157.055q-.076.036-.142.088q-.066.051-.118.116q-.022.028-.042.057q-.126.189-.126.416v9q0 2.25 2.25 2.25h15q2.25 0 2.25-2.25v-9q0-.223-.122-.41l-.004-.006q-.051-.077-.12-.139q-.068-.063-.15-.106q-.082-.044-.172-.066T21 10.25q-.223 0-.41.122zM7.25 6.75h9.5v6.182L12 16.099l-4.75-3.167zm9.5-1.5h-9.5V4q0-.75.75-.75h8q.75 0 .75.75zM3.75 20v-7.599l7.834 5.223q.092.062.199.094q.106.032.217.032t.217-.032t.199-.094l7.834-5.223V20q0 .75-.75.75h-15q-.75 0-.75-.75");
}

</style>
