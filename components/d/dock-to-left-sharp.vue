<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qf43jb_jq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:dock-to-left-sharp" /></template>
<style>
.qf43jb_jq {
  fill: currentColor;
  d: path("M5 19h9V5H5zm-2 2V3h18v18z");
}

</style>
