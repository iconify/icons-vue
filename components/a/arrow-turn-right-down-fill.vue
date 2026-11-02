<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t_plekbbk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:arrow-turn-right-down-fill" /></template>
<style>
.t_plekbbk {
  fill: currentColor;
  d: path("M14 6a3 3 0 0 1 3 3v5.586l3.293-3.293a.999.999 0 1 1 1.414 1.414l-5 5a1 1 0 0 1-1.414 0l-5-5a.999.999 0 1 1 1.414-1.414L15 14.586V9a.997.997 0 0 0-1-1H3a1 1 0 0 1 0-2Z");
}

</style>
