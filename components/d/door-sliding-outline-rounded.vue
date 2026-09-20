<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fy2jb2cxl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:door-sliding-outline-rounded" /></template>
<style>
.fy2jb2cxl {
  fill: currentColor;
  d: path("M9.191 12.54q-.23-.23-.23-.54t.23-.54t.54-.23t.54.23t.229.54t-.23.54t-.54.23t-.539-.23m4.539 0q-.23-.23-.23-.54t.23-.54t.54-.23t.539.23t.23.54t-.23.54t-.54.23t-.54-.23M5 20q-.213 0-.357-.143T4.5 19.5q0-.208.16-.322q.161-.114.34-.178h.5V5.616q0-.691.463-1.153T7.116 4h9.769q.69 0 1.153.463t.462 1.153V19h.5q.214 0 .357.143t.143.357t-.143.357T19 20zm1.5-1h5V5H7.116q-.231 0-.424.192t-.192.424zm6 0h5V5.616q0-.231-.192-.424T16.884 5H12.5zm-.5-7.5");
}

</style>
