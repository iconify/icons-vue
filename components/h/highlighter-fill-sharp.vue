<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vy7yq5t-g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:highlighter-fill-sharp" /></template>
<style>
.vy7yq5t-g {
  fill: currentColor;
  d: path("M13.293 3.293a1 1 0 0 1 1.414 0l6 6a1 1 0 0 1 0 1.414l-7 7a1 1 0 0 1-1.414 0L12 17.414l-3.293 3.293A1 1 0 0 1 8 21H3a1 1 0 0 1-1-1v-3c0-.265.105-.52.293-.707L6.586 12l-.293-.293a.997.997 0 0 1 0-1.414ZM4 17.414V19h3.586l3-3L8 13.414Z");
}

</style>
