<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dz7u5x0el"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-frame-share-sharp" /></template>
<style>
.dz7u5x0el {
  fill: currentColor;
  d: path("M2 17V7h15.329l-1.02 1H3v8h8.116v1zm11.5-1.5v-4h6.887l-2.095-2.1l.708-.689L22.288 12L19 15.288l-.713-.713l2.1-2.075H14.5v3zm-2.384-.885H4.385v-5.23h9.52h-2.79z");
}

</style>
