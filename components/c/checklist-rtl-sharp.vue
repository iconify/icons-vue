<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nefjy4b4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:checklist-rtl-sharp" /></template>
<style>
.nefjy4b4y {
  fill: currentColor;
  d: path("m16.375 19l-3.55-3.55l1.4-1.4l2.125 2.125l4.25-4.25L22 13.35zm0-8l-3.55-3.55l1.4-1.4l2.125 2.125l4.25-4.25L22 5.35zM2 17v-2h9v2zm0-8V7h9v2z");
}

</style>
