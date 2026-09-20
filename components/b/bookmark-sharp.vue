<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="n889bjj8d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-sharp" /></template>
<style>
.n889bjj8d {
  fill: currentColor;
  d: path("M6 19.5V4h12v15.5l-6-2.583z");
}

</style>
