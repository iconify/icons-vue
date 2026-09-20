<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nm8i13gdk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:android-cell-5-bar-sharp" /></template>
<style>
.nm8i13gdk {
  fill: currentColor;
  d: path("M2 19v-4.712h1.692V19zm4.577 0v-6.577h1.692V19zm4.577 0V9.654h1.692V19zm4.577 0V7.789h1.692V19zm4.577 0V5H22v14z");
}

</style>
