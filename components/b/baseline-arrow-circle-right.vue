<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0bzjabjl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-arrow-circle-right" /></template>
<style>
.y0bzjabjl {
  fill: currentColor;
  d: path("M22 12c0-5.52-4.48-10-10-10S2 6.48 2 12s4.48 10 10 10s10-4.48 10-10m-10 1H8v-2h4V8l4 4l-4 4z");
}

</style>
