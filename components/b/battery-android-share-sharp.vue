<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g5rzwpu4b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:battery-android-share-sharp" /></template>
<style>
.g5rzwpu4b {
  fill: currentColor;
  d: path("M2 17V7h15.329l-2.193 2.116h-4.02V17zm11.5-1.5v-4h6.887l-2.095-2.1l.708-.689L22.288 12L19 15.288l-.713-.713l2.1-2.075H14.5v3z");
}

</style>
