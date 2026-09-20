<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ho-4fmber"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:chrome-reader-mode-sharp" /></template>
<style>
.ho-4fmber {
  fill: currentColor;
  d: path("M3 19V5h18v14zm9.5-1H20V6h-7.5zm1.077-8.308h5.346v-.884h-5.346zm0 2.5h5.346v-.884h-5.346zm0 2.5h5.346v-.884h-5.346z");
}

</style>
