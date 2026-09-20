<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="h55r_ow8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:breaking-news-outline-sharp" /></template>
<style>
.h55r_ow8g {
  fill: currentColor;
  d: path("M6.23 16.77h1.54v-1.54H6.23zm.27-3h1V7.5h-1zm5 2.73h6v-1h-6zm0-4h6v-1h-6zm0-4h6v-1h-6zM3 20V4h18v16zm1-1h16V5H4zm0 0V5z");
}

</style>
