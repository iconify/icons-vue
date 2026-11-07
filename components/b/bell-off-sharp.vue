<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="exnddub3y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bell-off-sharp" /></template>
<style>
.exnddub3y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("M12 17H4v-2c0-1 1-1 1-2v-3c0-1.678.59-3.219 1.575-4.425m3.652-2.348A7 7 0 0 1 19 10v2m-1 5h-6m-3 0v1a3 3 0 0 0 6 0v-1M3 2l19 19");
}

</style>
