<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="pyubxpfrq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:align-space-between" /></template>
<style>
.pyubxpfrq {
  fill: currentColor;
  d: path("M7.5 6V4H3V3h18v1h-4.5v2zM3 21v-1h4.5v-2h9v2H21v1z");
}

</style>
