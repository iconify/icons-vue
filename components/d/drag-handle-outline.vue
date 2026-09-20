<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y8jm_xmse"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:drag-handle-outline" /></template>
<style>
.y8jm_xmse {
  fill: currentColor;
  d: path("M5 14.5v-1h14v1zm0-4v-1h14v1z");
}

</style>
