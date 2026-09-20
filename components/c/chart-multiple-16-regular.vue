<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="admioj00n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:chart-multiple-16-regular" /></template>
<style>
.admioj00n {
  fill: currentColor;
  d: path("M12 7c0-.684.343-1.287.866-1.648A5.574 5.574 0 0 0 7.43 1a.436.436 0 0 0-.43.445V6.5a.5.5 0 0 0 .5.5zM8 2.035A4.574 4.574 0 0 1 11.965 6H8zM1 7.501a5.5 5.5 0 0 0 5 5.477v-1.005a4.5 4.5 0 0 1-1-8.716V7a2 2 0 0 0 2 2h2c0-.364.097-.706.268-1H7a1 1 0 0 1-1-1V2.571c0-.294-.253-.526-.542-.47A5.5 5.5 0 0 0 1 7.5M14 6a1 1 0 0 0-1 1v7a1 1 0 1 0 2 0V7a1 1 0 0 0-1-1m-3 2a1 1 0 0 0-1 1v5a1 1 0 1 0 2 0V9a1 1 0 0 0-1-1m-4 3a1 1 0 1 1 2 0v3a1 1 0 1 1-2 0z");
}

</style>
