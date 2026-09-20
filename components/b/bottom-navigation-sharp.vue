<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="q_9v_pbxm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bottom-navigation-sharp" /></template>
<style>
.q_9v_pbxm {
  fill: currentColor;
  d: path("M4 20V4h16v16zm1-4.615h14V5H5z");
}

</style>
