<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="maj-d8bvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:barn-fill-round" /></template>
<style>
.maj-d8bvi {
  fill: currentColor;
  d: path("M3 22a1 1 0 0 1 0-2v-8.667c0-1.082.351-2.134 1-3l1.73-2.306a5 5 0 0 1 1.427-1.288l2.271-1.362a5 5 0 0 1 5.144 0l2.271 1.362c.555.332 1.04.77 1.427 1.288L20 8.333c.649.866 1 1.918 1 3V20a1 1 0 0 1 0 2Zm9-10a2 2 0 1 0 .001-3.999A2 2 0 0 0 12 12m3 6a2 2 0 0 0-2-2h-2a2 2 0 0 0-2 2v2h6Z");
}

</style>
