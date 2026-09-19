<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rq1frrb-x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-nightlight-round" /></template>
<style>
.rq1frrb-x {
  fill: currentColor;
  d: path("M12.01 12c0-3.57 2.2-6.62 5.31-7.87c.89-.36.75-1.69-.19-1.9c-1.1-.24-2.27-.3-3.48-.14c-4.51.6-8.12 4.31-8.59 8.83C4.44 16.93 9.13 22 15.01 22c.73 0 1.43-.08 2.12-.23c.95-.21 1.1-1.53.2-1.9A8.46 8.46 0 0 1 12.01 12");
}

</style>
