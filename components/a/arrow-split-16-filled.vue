<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="r3k_wqbeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-split-16-filled" /></template>
<style>
.r3k_wqbeh {
  fill: currentColor;
  d: path("M8 2a.75.75 0 0 1 .75.75V6H11a1.5 1.5 0 0 1 1.5 1.5v3.94l.72-.72a.75.75 0 1 1 1.06 1.06l-2 2a.75.75 0 0 1-1.06 0l-2-2a.75.75 0 1 1 1.06-1.06l.72.72V7.5H5v3.94l.72-.72a.75.75 0 0 1 1.06 1.06l-2 2a.75.75 0 0 1-1.06 0l-2-2a.75.75 0 1 1 1.06-1.06l.72.72V7.5A1.5 1.5 0 0 1 5 6h2.25V2.75A.75.75 0 0 1 8 2");
}

</style>
