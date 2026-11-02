<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="t9x8lz15h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chart-treemap-fill" /></template>
<style>
.t9x8lz15h {
  fill: currentColor;
  d: path("M9 2v20H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3Zm2 7V2h8a3 3 0 0 1 3 3v4Zm4 13h-4V11h4Zm7-11v8a3 3 0 0 1-3 3h-2V11Z");
}

</style>
