<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bcd_hg36l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:mail-inbox-checkmark-24-filled" /></template>
<style>
.bcd_hg36l {
  fill: currentColor;
  d: path("M22 6.5a5.5 5.5 0 1 1-11 0a5.5 5.5 0 0 1 11 0m-2.146-2.354a.5.5 0 0 0-.708 0L15.5 7.793l-1.646-1.647a.5.5 0 0 0-.708.708l2 2a.5.5 0 0 0 .708 0l4-4a.5.5 0 0 0 0-.708m-.354 8.122V14H15a.75.75 0 0 0-.75.75a2.25 2.25 0 0 1-4.5 0l-.007-.102A.75.75 0 0 0 9 14H4.5V7.25c0-.966.784-1.75 1.75-1.75h3.826a6.5 6.5 0 0 1 .422-1.5H6.25A3.25 3.25 0 0 0 3 7.25v11.5A3.25 3.25 0 0 0 6.25 22h11.5A3.25 3.25 0 0 0 21 18.75v-7.56a6.5 6.5 0 0 1-1.5 1.078");
}

</style>
