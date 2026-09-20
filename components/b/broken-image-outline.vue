<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xfh5qwbpx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:broken-image-outline" /></template>
<style>
.xfh5qwbpx {
  fill: currentColor;
  d: path("M5.616 20q-.691 0-1.153-.462T4 18.384V5.616q0-.691.463-1.153T5.616 4h12.769q.69 0 1.153.463T20 5.616v12.769q0 .69-.462 1.153T18.384 20zM6 13.287l4-4l4 4l4-4l1 1V5.616q0-.27-.173-.443T18.385 5H5.615q-.269 0-.442.173T5 5.616v6.67zM5.616 19h12.769q.269 0 .442-.173t.173-.442v-6.677l-1-1l-4 4l-4-4l-4 4l-1-1v4.677q0 .269.173.442t.443.173M5 19v-7.292v1V5z");
}

</style>
