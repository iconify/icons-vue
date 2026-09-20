<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="w-bxbdctz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:magnification-small-sharp" /></template>
<style>
.w-bxbdctz {
  fill: currentColor;
  d: path("M5.5 10.5h3v-3h-3zM3 19V5h18v14z");
}

</style>
