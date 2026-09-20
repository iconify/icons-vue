<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bxj8ntb2b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bar-chart-off-sharp" /></template>
<style>
.bxj8ntb2b {
  fill: currentColor;
  d: path("M5 19V9.808h3V19zm5.5 0v-8.5l3 3V19zm3-8.311l-3-3V5h3zm5.5 5.5l-1.961-1.962v-.035H19zm.833 5.07L2.74 4.168l.713-.713l17.092 17.092z");
}

</style>
