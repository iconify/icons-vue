<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m5czdbcwn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:egg-outline-sharp" /></template>
<style>
.m5czdbcwn {
  fill: currentColor;
  d: path("M13 18h1v-2h-1q-1.25 0-2.125-.875T10 13v-1H8v1q0 2.075 1.463 3.538T13 18m-5.962.963Q5 16.925 5 14q0-1.925.638-3.875t1.65-3.537T9.55 4T12 3q1.225 0 2.463 1t2.25 2.588t1.65 3.537T19 14q0 2.925-2.037 4.963T12 21t-4.962-2.037m8.5-1.426Q17 16.075 17 14q0-1.425-.488-3t-1.225-2.912t-1.612-2.213T12.013 5t-1.675.875t-1.625 2.213T7.488 11T7 14q0 2.075 1.463 3.538T12 19t3.538-1.463M12 12");
}

</style>
