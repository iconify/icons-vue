<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lq74pnbnj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-diamond-outline-sharp" /></template>
<style>
.lq74pnbnj {
  fill: currentColor;
  d: path("M11 16h2v-3h3v-2h-3V8h-2v3H8v2h3zm1.025 6.85L1.225 12l10.8-10.825L22.775 12zM12 20l7.975-8L12 4l-7.975 8zm0-8");
}

</style>
