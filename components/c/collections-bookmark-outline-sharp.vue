<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="qcf6x4iwj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:collections-bookmark-outline-sharp" /></template>
<style>
.qcf6x4iwj {
  fill: currentColor;
  d: path("M7.5 16h12V4h-2v6.116l-2-1.193l-2 1.193V4h-6zm-1 1V3h14v14zm-3 3V6.616h1V19h12.385v1zm4-16v12zm6 6.116l2-1.193l2 1.193l-2-1.193z");
}

</style>
