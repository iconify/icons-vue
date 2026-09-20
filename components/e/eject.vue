<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eg1qu2bhb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:eject" /></template>
<style>
.eg1qu2bhb {
  fill: currentColor;
  d: path("M5 19v-2h14v2zm.35-4L12 5l6.65 10z");
}

</style>
