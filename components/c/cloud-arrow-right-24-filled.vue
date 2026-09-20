<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jmyuhuwkj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:cloud-arrow-right-24-filled" /></template>
<style>
.jmyuhuwkj {
  fill: currentColor;
  d: path("M12 3a6 6 0 0 0-5.92 5.02A4.5 4.5 0 0 0 6.5 17h3.519a6.5 6.5 0 0 1 11.955-4.008Q22 12.75 22 12.5a4.5 4.5 0 0 0-4.08-4.48A6 6 0 0 0 12 3m4.5 8a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11m-3 5a.5.5 0 0 0 0 1h4.793l-1.647 1.646a.5.5 0 0 0 .708.708l2.5-2.5a.5.5 0 0 0 0-.708l-2.5-2.5a.5.5 0 0 0-.708.708L18.293 16z");
}

</style>
