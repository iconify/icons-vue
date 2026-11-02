<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y_p5yv07v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hard-hat-fill" /></template>
<style>
.y_p5yv07v {
  fill: currentColor;
  d: path("M20 11v4H4v-4a6.01 6.01 0 0 1 5-5.918V5a2 2 0 0 1 2-2h2a2 2 0 0 1 2 2v.082A6.01 6.01 0 0 1 20 11M2.171 17h19.658A3 3 0 0 1 19 21H5a3 3 0 0 1-2.829-4");
}

</style>
