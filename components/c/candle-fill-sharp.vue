<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n_t67yi5v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:candle-fill-sharp" /></template>
<style>
.n_t67yi5v {
  fill: currentColor;
  d: path("M15.595 10H16a1 1 0 0 1 1 1v10a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1V11a1 1 0 0 1 1-1h.405c-.406-1.086-.333-2.597.527-3.457c.402-.403.738-.97 1.015-1.464q.65-1.173 1.117-2.43a1 1 0 0 1 1.917.155c.186.928.762 1.67 1.508 2.229q.057.043.107.093c.958.959 1.237 2.227 1.237 3.541c.002.455-.079.907-.238 1.333");
}

</style>
