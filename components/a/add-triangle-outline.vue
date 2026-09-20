<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="meja6hbnv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-triangle-outline" /></template>
<style>
.meja6hbnv {
  fill: currentColor;
  d: path("M1 20L12 1l11 19zm3.475-2h15.05L12 5zM11 16.5h2v-2h2v-2h-2v-2h-2v2H9v2h2zm1-3");
}

</style>
