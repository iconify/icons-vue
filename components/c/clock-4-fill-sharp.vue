<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="tyjunpvwq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:clock-4-fill-sharp" /></template>
<style>
.tyjunpvwq {
  fill: currentColor;
  d: path("M2 12C2 6.477 6.477 2 12 2s10 4.477 10 10s-4.477 10-10 10S2 17.523 2 12m11-.5V7a1 1 0 0 0-2 0v5a1 1 0 0 0 .4.8l4 3a1 1 0 0 0 1.2-1.6Z");
}

</style>
