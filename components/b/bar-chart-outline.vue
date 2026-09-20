<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bjcdftdyi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:bar-chart-outline" /></template>
<style>
.bjcdftdyi {
  fill: currentColor;
  d: path("M16 20v-7h4v7zm-6 0V4h4v16zm-6 0V9h4v11z");
}

</style>
