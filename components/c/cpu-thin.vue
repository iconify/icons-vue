<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="h4wwztblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:cpu-thin" /></template>
<style>
.h4wwztblv {
  fill: currentColor;
  d: path("M152 100h-48a4 4 0 0 0-4 4v48a4 4 0 0 0 4 4h48a4 4 0 0 0 4-4v-48a4 4 0 0 0-4-4m-4 48h-40v-40h40Zm84 0h-20v-40h20a4 4 0 0 0 0-8h-20V56a12 12 0 0 0-12-12h-44V24a4 4 0 0 0-8 0v20h-40V24a4 4 0 0 0-8 0v20H56a12 12 0 0 0-12 12v44H24a4 4 0 0 0 0 8h20v40H24a4 4 0 0 0 0 8h20v44a12 12 0 0 0 12 12h44v20a4 4 0 0 0 8 0v-20h40v20a4 4 0 0 0 8 0v-20h44a12 12 0 0 0 12-12v-44h20a4 4 0 0 0 0-8m-28 52a4 4 0 0 1-4 4H56a4 4 0 0 1-4-4V56a4 4 0 0 1 4-4h144a4 4 0 0 1 4 4Z");
}

</style>
