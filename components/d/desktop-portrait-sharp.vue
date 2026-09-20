<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v1f-sh47t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:desktop-portrait-sharp" /></template>
<style>
.v1f-sh47t {
  fill: currentColor;
  d: path("M11 18h5V9h-5zm-3-3h1.5V7.5H13V6H8zm12 7H4V2h16z");
}

</style>
