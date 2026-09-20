<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="bpcttb7pa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:file-archive-bold" /></template>
<style>
.bpcttb7pa {
  fill: currentColor;
  d: path("m216.49 79.51l-56-56A12 12 0 0 0 152 20H56a20 20 0 0 0-20 20v176a20 20 0 0 0 20 20h144a20 20 0 0 0 20-20V88a12 12 0 0 0-3.51-8.49M183 80h-23V57Zm-67 132v-20h8a12 12 0 0 0 0-24h-8v-16h8a12 12 0 0 0 0-24h-8v-12a12 12 0 0 0-24 0v12h-8a12 12 0 0 0 0 24h8v16h-8a12 12 0 0 0 0 24h8v20H60V44h76v48a12 12 0 0 0 12 12h48v108Z");
}

</style>
