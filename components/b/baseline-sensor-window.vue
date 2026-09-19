<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="xf4vw1bbd"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-sensor-window" /></template>
<style>
.xf4vw1bbd {
  fill: currentColor;
  d: path("M18 4v16H6V4zm0-2H6c-1.1 0-2 .9-2 2v16c0 1.1.9 2 2 2h12c1.1 0 2-.9 2-2V4c0-1.1-.9-2-2-2M7 19h10v-6H7zm3-9h4v1h3V5H7v6h3z");
}

</style>
