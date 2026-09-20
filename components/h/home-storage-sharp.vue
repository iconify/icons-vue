<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="dy2ezbbqh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:home-storage-sharp" /></template>
<style>
.dy2ezbbqh {
  fill: currentColor;
  d: path("M5 21L3 9h18l-2 12zm4-6h6v-2H9zM5 8V6h14v2zm2-3V3h10v2z");
}

</style>
