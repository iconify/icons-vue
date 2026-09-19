<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="zg388nf3w"/><path class="i_dcz75ne"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:instawork" /></template>
<style>
.i_dcz75ne {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.85 33.744L24 25.176l4.15 8.568c1.458 3.007 5.741 3.007 7.2 0l7.749-16a4 4 0 0 0-7.2-3.487l-4.15 8.568l-4.15-8.568a4 4 0 0 0-7.198 0l-4.15 8.568");
}

.zg388nf3w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m4.901 17.744l7.75 16a4 4 0 0 0 7.199-3.488l-7.75-16a4 4 0 0 0-7.199 3.488");
}

</style>
