<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqu2z7j_m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:density-large-outline" /></template>
<style>
.oqu2z7j_m {
  fill: currentColor;
  d: path("M3 21v-2h18v2zM3 5V3h18v2z");
}

</style>
