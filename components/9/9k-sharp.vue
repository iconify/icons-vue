<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="aa8mkze8g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:9k-sharp" /></template>
<style>
.aa8mkze8g {
  fill: currentColor;
  d: path("M6.885 14.692h3.884V9.308H6.885v3.077h3v1.423h-3zm.884-3.076v-1.539h2.116v1.539zm5.116 3.076h.884v-2.365l2.289 2.365h1.211l-2.634-2.73l2.634-2.654h-1.173l-2.327 2.327V9.308h-.885zM4 20V4h16v16z");
}

</style>
