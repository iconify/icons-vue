<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="j8nblncxb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:diamond-minus-fill" /></template>
<style>
.j8nblncxb {
  fill: currentColor;
  d: path("m17.707 17.707l-4 4a2.414 2.414 0 0 1-3.414 0l-8-8a2.414 2.414 0 0 1 0-3.414l8-8a2.414 2.414 0 0 1 3.414 0l8 8a2.414 2.414 0 0 1 0 3.414ZM15 11H9a1 1 0 0 0 0 2h6a1 1 0 0 0 0-2");
}

</style>
