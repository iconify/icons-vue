<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ussh_vwik"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:1k-outline-sharp" /></template>
<style>
.ussh_vwik {
  fill: currentColor;
  d: path("M12.539 14.692h.884v-2.365l2.289 2.365h1.229l-2.652-2.73l2.651-2.654h-1.19l-2.327 2.326V9.308h-.885zm-3.731 0h.884V9.308H7.308v.884h1.5zM4 20V4h16v16zm1-1h14V5H5zm0 0V5z");
}

</style>
