<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="kjb024bcl"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:exposure-plus-1-outline" /></template>
<style>
.kjb024bcl {
  fill: currentColor;
  d: path("M6 17v-3H3v-2h3V9h2v3h3v2H8v3zm9.75 2V8.05l-2.3 1.65l-1.15-1.75L16.4 5H18v14z");
}

</style>
