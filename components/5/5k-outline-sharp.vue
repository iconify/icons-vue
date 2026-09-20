<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="x_t-icb-r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:5k-outline-sharp" /></template>
<style>
.x_t-icb-r {
  fill: currentColor;
  d: path("M12.885 14.692h.884v-2.365l2.289 2.365h1.229l-2.652-2.73l2.652-2.654h-1.19l-2.328 2.327V9.308h-.884zm-6 0h3.884v-3.076h-3v-1.424h3v-.884H6.885v3.077h3v1.423h-3zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
