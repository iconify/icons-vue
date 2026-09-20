<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="y1_8nwvhw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-wrap-20-regular" /></template>
<style>
.y1_8nwvhw {
  fill: currentColor;
  d: path("M14 4a3 3 0 1 1 0 6H6a2 2 0 1 0 0 4h10.293l-.647-.646a.5.5 0 0 1 .708-.708l1.5 1.5a.5.5 0 0 1 0 .708l-1.5 1.5a.5.5 0 0 1-.708-.708l.647-.646H6a3 3 0 1 1 0-6h8a2 2 0 1 0 0-4H3.5a.5.5 0 0 1 0-1z");
}

</style>
