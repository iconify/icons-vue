<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="m_draabch"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:home-improvement-and-tools-outline-sharp" /></template>
<style>
.m_draabch {
  fill: currentColor;
  d: path("M7.962 3h8.076L14 5.892v12.685l-2 2l-2-2V5.892zM11 10.5h2V5.6L14 4h-4l1 1.6zm2 1h-2v3h2zm0 6.577V15.5h-2v2.577l1 1zM12 15.5");
}

</style>
