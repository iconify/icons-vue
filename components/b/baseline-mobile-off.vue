<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="r2e2o-fby"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ic:baseline-mobile-off" /></template>
<style>
.r2e2o-fby {
  fill: currentColor;
  d: path("M2.76 2.49L1.49 3.76L5 7.27V21c0 1.1.9 2 2 2h10c1.02 0 1.85-.77 1.98-1.75l1.72 1.72l1.27-1.27zM7 19V9.27L16.73 19zM17 5v9.17l2 2V3c0-1.1-.9-2-2-2H7c-.85 0-1.58.54-1.87 1.3L7.83 5z");
}

</style>
