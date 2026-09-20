<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ba0omcc7q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-exit-24-filled" /></template>
<style>
.ba0omcc7q {
  fill: currentColor;
  d: path("M6.5 3A3.5 3.5 0 0 0 3 6.5v11A3.5 3.5 0 0 0 6.5 21H15a1 1 0 1 0 0-2H6.5A1.5 1.5 0 0 1 5 17.5v-11A1.5 1.5 0 0 1 6.5 5H15a1 1 0 1 0 0-2zm11.207 4.293a1 1 0 1 0-1.414 1.414L18.586 11H9a1 1 0 1 0 0 2h9.586l-2.293 2.293a1 1 0 0 0 1.414 1.414l4-4a1 1 0 0 0 0-1.414z");
}

</style>
