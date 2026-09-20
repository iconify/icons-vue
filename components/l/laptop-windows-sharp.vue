<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ikl58_bwl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:laptop-windows-sharp" /></template>
<style>
.ikl58_bwl {
  fill: currentColor;
  d: path("M0 20v-2h4v-1H2V3h20v14h-2v1h4v2z");
}

</style>
