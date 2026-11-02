<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_yfa8b4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-u-turn-right-down-bulk-sharp" /></template>
<style>
.t_yfa8b4m {
  fill: currentColor;
  d: path("m14.293 21.707l-4-4a.999.999 0 1 1 1.414-1.414L14 18.586V4H6v9a1 1 0 0 1-2 0V3a1 1 0 0 1 1-1h10a1 1 0 0 1 1 1v15.586l2.293-2.293a.999.999 0 1 1 1.414 1.414l-4 4a1 1 0 0 1-1.414 0");
}

</style>
