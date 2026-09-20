<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="oqaz02bql"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:borg-outline-sharp" /></template>
<style>
.oqaz02bql {
  fill: currentColor;
  d: path("M4 16.587V7.414l8-4.637l8 4.637v9.173l-8 4.636zm4.673-1.24V12.5H5v3.489l6.5 3.802v-4.445zm0-6.693H11.5V4.21L5 8.012V11.5h3.673zm1 5.692h4.635V9.673H9.673zm5.635 1H12.5v4.445l6.5-3.802V12.5h-3.692zm0-6.692V11.5H19V8.012L12.5 4.21v4.444z");
}

</style>
