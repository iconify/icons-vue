<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="uopn6gofb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:call-missed-rounded" /></template>
<style>
.uopn6gofb {
  fill: currentColor;
  d: path("M5 9.617v4.787q0 .213-.143.357t-.357.143t-.357-.143T4 14.404V8.71q0-.348.23-.577q.23-.23.578-.23H10.5q.214 0 .357.143t.143.357t-.143.356t-.357.144H5.708l5.946 5.946q.173.173.442.173t.443-.173l6.419-6.42q.146-.145.344-.152t.364.159q.159.165.162.354t-.162.353l-6.433 6.433q-.243.242-.54.354q-.299.111-.597.111t-.596-.111t-.54-.354z");
}

</style>
