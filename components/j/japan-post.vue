<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="gu4mwobih"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:japan-post" /></template>
<style>
.gu4mwobih {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 9.5h39v5.7h-39zm0 9.8V25h16.65v13.5h5.7V25H43.5v-5.7z");
}

</style>
