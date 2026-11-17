<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="umkrg_z4m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cooktop-fill" /></template>
<style>
.umkrg_z4m {
  fill: currentColor;
  d: path("M5 2h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3m.236 4.832a3 3 0 1 0 5.527 2.335a3 3 0 0 0-5.527-2.335M13 8a3 3 0 1 0 6 0a3 3 0 0 0-6 0M9 8a1 1 0 1 1-2 0a1 1 0 0 1 2 0m6 0a1 1 0 1 1 2 0a1 1 0 0 1-2 0M5 16v.001a3 3 0 1 0 6 0A3 3 0 0 0 5 16m8 0a3 3 0 1 0 6 0a3 3 0 0 0-6 0m-6 0a1 1 0 1 1 2 0a1 1 0 0 1-2 0m8 0a1 1 0 1 1 2 0a1 1 0 0 1-2 0");
}

</style>
