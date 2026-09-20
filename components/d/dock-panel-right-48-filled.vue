<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="clqa3466w"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dock-panel-right-48-filled" /></template>
<style>
.clqa3466w {
  fill: currentColor;
  d: path("M44 13.25A6.25 6.25 0 0 0 37.75 7h-27.5A6.25 6.25 0 0 0 4 13.25v21.5A6.25 6.25 0 0 0 10.25 41h27.5A6.25 6.25 0 0 0 44 34.75zM10.25 38.5a3.75 3.75 0 0 1-3.75-3.75v-21.5a3.75 3.75 0 0 1 3.75-3.75h19.5v29z");
}

</style>
