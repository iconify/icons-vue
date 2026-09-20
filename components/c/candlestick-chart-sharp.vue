<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="sp0dfpbng"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:candlestick-chart-sharp" /></template>
<style>
.sp0dfpbng {
  fill: currentColor;
  d: path("M8 19v-2H6V7h2V5h1v2h2v10H9v2zm7 0v-4.615h-2V8.808h2V5h1v3.808h2v5.577h-2V19z");
}

</style>
