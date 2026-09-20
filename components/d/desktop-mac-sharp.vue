<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_15p-c5d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:desktop-mac-sharp" /></template>
<style>
.y_15p-c5d {
  fill: currentColor;
  d: path("M8 21v-1l2-2H2V3h20v15h-8l2 2v1z");
}

</style>
