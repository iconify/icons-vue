<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8i9nwwrp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:add-2-outline" /></template>
<style>
.y8i9nwwrp {
  fill: currentColor;
  d: path("M11 21v-8H3v-2h8V3h2v8h8v2h-8v8z");
}

</style>
