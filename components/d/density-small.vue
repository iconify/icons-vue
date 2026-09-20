<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="waf4xobye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:density-small" /></template>
<style>
.waf4xobye {
  fill: currentColor;
  d: path("M3 22v-2h18v2zm0-6v-2h18v2zm0-6V8h18v2zm0-6V2h18v2z");
}

</style>
