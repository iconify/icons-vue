<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="wh240kb3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dual-screen-arrow-up-20-filled" /></template>
<style>
.wh240kb3y {
  fill: currentColor;
  d: path("M19 5.5a4.5 4.5 0 1 1-9 0a4.5 4.5 0 0 1 9 0m-4.854-2.353l-2 2a.5.5 0 0 0 .708.707L14 4.707V7.5a.5.5 0 0 0 1 0V4.707l1.146 1.147a.5.5 0 0 0 .708-.708l-2-2A.5.5 0 0 0 14.503 3h-.006a.5.5 0 0 0-.348.144zM14.5 11c1.33 0 2.55-.472 3.5-1.257V16a2 2 0 0 1-2 2h-5.5V9.275a5.5 5.5 0 0 0 4 1.725m-5-3.206A5.5 5.5 0 0 1 9.022 6H4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h5.5zM6 15.5a.5.5 0 0 1 .5-.5h1a.5.5 0 0 1 0 1h-1a.5.5 0 0 1-.5-.5m6.5-.5a.5.5 0 0 0 0 1h1a.5.5 0 0 0 0-1z");
}

</style>
