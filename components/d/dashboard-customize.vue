<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="yx9rvkkeq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dashboard-customize" /></template>
<style>
.yx9rvkkeq {
  fill: currentColor;
  d: path("M3 3h8v8H3zm10 0h8v8h-8zM3 13h8v8H3zm13 0h2v3h3v2h-3v3h-2v-3h-3v-2h3z");
}

</style>
