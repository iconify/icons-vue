<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g_970ccbu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:format-align-right-outline" /></template>
<style>
.g_970ccbu {
  fill: currentColor;
  d: path("M4 5V4h16v1zm6 3.75v-1h10v1zM4 12.5v-1h16v1zm6 3.75v-1h10v1zM4 20v-1h16v1z");
}

</style>
