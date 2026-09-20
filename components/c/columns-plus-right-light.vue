<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="mckh86lyt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:columns-plus-right-light" /></template>
<style>
.mckh86lyt {
  fill: currentColor;
  d: path("M80 34H56a14 14 0 0 0-14 14v160a14 14 0 0 0 14 14h24a14 14 0 0 0 14-14V48a14 14 0 0 0-14-14m2 174a2 2 0 0 1-2 2H56a2 2 0 0 1-2-2V48a2 2 0 0 1 2-2h24a2 2 0 0 1 2 2Zm70-174h-24a14 14 0 0 0-14 14v160a14 14 0 0 0 14 14h24a14 14 0 0 0 14-14V48a14 14 0 0 0-14-14m2 174a2 2 0 0 1-2 2h-24a2 2 0 0 1-2-2V48a2 2 0 0 1 2-2h24a2 2 0 0 1 2 2Zm92-80a6 6 0 0 1-6 6h-18v18a6 6 0 0 1-12 0v-18h-18a6 6 0 0 1 0-12h18v-18a6 6 0 0 1 12 0v18h18a6 6 0 0 1 6 6");
}

</style>
