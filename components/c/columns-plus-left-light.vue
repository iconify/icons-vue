<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="nbro7ar3u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:columns-plus-left-light" /></template>
<style>
.nbro7ar3u {
  fill: currentColor;
  d: path("M128 34h-24a14 14 0 0 0-14 14v160a14 14 0 0 0 14 14h24a14 14 0 0 0 14-14V48a14 14 0 0 0-14-14m2 174a2 2 0 0 1-2 2h-24a2 2 0 0 1-2-2V48a2 2 0 0 1 2-2h24a2 2 0 0 1 2 2Zm70-174h-24a14 14 0 0 0-14 14v160a14 14 0 0 0 14 14h24a14 14 0 0 0 14-14V48a14 14 0 0 0-14-14m2 174a2 2 0 0 1-2 2h-24a2 2 0 0 1-2-2V48a2 2 0 0 1 2-2h24a2 2 0 0 1 2 2ZM70 128a6 6 0 0 1-6 6H46v18a6 6 0 0 1-12 0v-18H16a6 6 0 0 1 0-12h18v-18a6 6 0 0 1 12 0v18h18a6 6 0 0 1 6 6");
}

</style>
