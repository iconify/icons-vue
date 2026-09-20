<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="mst09jbge"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dashboard-customize-outline-sharp" /></template>
<style>
.mst09jbge {
  fill: currentColor;
  d: path("M3 3h8v8H3zm2 2v4zm8-2h8v8h-8zm2 2v4zM3 13h8v8H3zm2 2v4zm11-2h2v3h3v2h-3v3h-2v-3h-3v-2h3zm-1-8v4h4V5zM5 5v4h4V5zm0 10v4h4v-4z");
}

</style>
