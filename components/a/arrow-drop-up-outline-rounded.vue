<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="wygfzcclm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:arrow-drop-up-outline-rounded" /></template>
<style>
.wygfzcclm {
  fill: currentColor;
  d: path("M9.162 13.5q-.182 0-.293-.124t-.111-.288q0-.042.13-.284l2.678-2.677q.092-.093.199-.143t.235-.05t.235.05t.2.143l2.677 2.677q.055.056.093.129q.037.073.037.157q0 .168-.11.289q-.112.121-.293.121z");
}

</style>
