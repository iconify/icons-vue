<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="v6bpzjyhe"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:calendar-date-32-filled" /></template>
<style>
.v6bpzjyhe {
  fill: currentColor;
  d: path("M29 24.5a4.5 4.5 0 0 1-4.5 4.5h-17A4.5 4.5 0 0 1 3 24.5V11h26zm-9.5-11c-1.68 0-3.25 1.236-3.25 3c0 .76.292 1.421.758 1.929a3.23 3.23 0 0 0-1.125 2.446c0 1.954 1.715 3.375 3.62 3.375c1.904 0 3.62-1.421 3.62-3.375c0-.993-.444-1.848-1.13-2.45a2.82 2.82 0 0 0 .757-1.925c0-1.764-1.57-3-3.25-3m-7.163.309a1 1 0 0 0-1.001.194c-.122.126-.232.26-.349.392c-.158.178-.384.426-.652.698c-.552.558-1.226 1.161-1.836 1.514a1 1 0 0 0 1.002 1.73c.525-.303 1.043-.71 1.499-1.117V23a1 1 0 1 0 2 0v-8.25a1 1 0 0 0-.663-.941m7.166 5.691c.99 0 1.62.706 1.62 1.375c0 .67-.63 1.375-1.62 1.375s-1.62-.706-1.62-1.375c0-.67.63-1.375 1.62-1.375m-.003-4c.804 0 1.25.555 1.25 1s-.446 1-1.25 1s-1.25-.555-1.25-1s.446-1 1.25-1m5-12.5A4.5 4.5 0 0 1 29 7.5V9H3V7.5A4.5 4.5 0 0 1 7.5 3z");
}

</style>
