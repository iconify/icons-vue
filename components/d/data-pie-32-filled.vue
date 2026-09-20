<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="uozterw1c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-pie-32-filled" /></template>
<style>
.uozterw1c {
  fill: currentColor;
  d: path("M17.31 3.288a1 1 0 0 1 .737-.275c5.916.277 10.663 5.024 10.94 10.94A1 1 0 0 1 27.988 15H18a1 1 0 0 1-1-1V4.012a1 1 0 0 1 .31-.724m-2.62 3a1 1 0 0 1 .31.724V14.5a2.5 2.5 0 0 0 2.5 2.5h7.488a1 1 0 0 1 1 1.047C25.7 24.145 20.667 29 14.5 29C8.149 29 3 23.851 3 17.5C3 11.332 7.855 6.299 13.953 6.013a1 1 0 0 1 .737.275");
}

</style>
