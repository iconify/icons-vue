<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cg3cczbbb"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:bookmark-add-sharp" /></template>
<style>
.cg3cczbbb {
  fill: currentColor;
  d: path("M17 9V7h-2V6h2V4h1v2h2v1h-2v2zM6 19.5V4h7.77q-.386.596-.578 1.197T13 6.5q0 1.742 1.157 3.012T17 10.958q.288.036.5.036t.5-.036V19.5l-6-2.583z");
}

</style>
