<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gfe_b861b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:film-script-bold" /></template>
<style>
.gfe_b861b {
  fill: currentColor;
  d: path("M200 20H56a20 20 0 0 0-20 20v176a20 20 0 0 0 20 20h144a20 20 0 0 0 20-20V40a20 20 0 0 0-20-20m-4 192H60V44h136ZM76 80a16 16 0 1 1 16 16a16 16 0 0 1-16-16m0 96a16 16 0 1 1 16 16a16 16 0 0 1-16-16m0-48a16 16 0 1 1 16 16a16 16 0 0 1-16-16");
}

</style>
