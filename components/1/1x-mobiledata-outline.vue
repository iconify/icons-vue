<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kk2lmcbyf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:1x-mobiledata-outline" /></template>
<style>
.kk2lmcbyf {
  fill: currentColor;
  d: path("M6 17V9H4V7h4v10zm4.35 0l3.15-5.3L10.65 7H13l1.65 2.75L16.35 7h2.3l-2.8 4.7L19 17h-2.35l-2-3.35l-2 3.35z");
}

</style>
