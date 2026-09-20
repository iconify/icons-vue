<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gx8g11bpy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:call-to-action-sharp" /></template>
<style>
.gx8g11bpy {
  fill: currentColor;
  d: path("M6.5 16.5h11v-2h-11zM3 19V5h18v14z");
}

</style>
