<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cw_b8gb5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:ev-station-outline-sharp" /></template>
<style>
.cw_b8gb5k {
  fill: currentColor;
  d: path("M6 10h6V5H6zm0 9h6v-7H6zm-2 2V3h10v9h3v7.5h2.25V9H18V6h.5V4.5h1V6h1V4.5h1V6h.5v3h-1.25v12H15.5v-7.5H14V21zm8-2H6zm-3.5 0l2.5-4H9.5v-3L7 16h1.5z");
}

</style>
