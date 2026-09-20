<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="d3dq-sznu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:line-weight-outline" /></template>
<style>
.d3dq-sznu {
  fill: currentColor;
  d: path("M3 20v-1h18v1zm0-3v-2h18v2zm0-4v-3h18v3zm0-5V4h18v4z");
}

</style>
