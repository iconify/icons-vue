<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="y0l-fbcox"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:line-start-square-outline" /></template>
<style>
.y0l-fbcox {
  fill: currentColor;
  d: path("M4.577 14.923h5.846V9.077H4.577zm6.846 1H3.577V8.077h7.846V11.5h9.5v1h-9.5zM7.5 12");
}

</style>
