<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="ugbu_qb_c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:filter-20-regular" /></template>
<style>
.ugbu_qb_c {
  fill: currentColor;
  d: path("M7.5 13h5a.5.5 0 0 1 .09.992L12.5 14h-5a.5.5 0 0 1-.09-.992zh5zm-2-4h9a.5.5 0 0 1 .09.992L14.5 10h-9a.5.5 0 0 1-.09-.992zh9zm-2-4h13a.5.5 0 0 1 .09.992L16.5 6h-13a.5.5 0 0 1-.09-.992zh13z");
}

</style>
