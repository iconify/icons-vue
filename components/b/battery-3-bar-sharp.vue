<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="u1zaf8sof"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-3-bar-sharp" /></template>
<style>
.u1zaf8sof {
  fill: currentColor;
  d: path("M7 22V4h3V2h4v2h3v18zm2-8h6V6H9z");
}

</style>
