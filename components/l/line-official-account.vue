<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kwwy-ku2e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:line-official-account" /></template>
<style>
.kwwy-ku2e {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.196 14.385v14.761h7.608m12.869-2.882V8.707c0-1.703-8.185-4.207-16.67-4.207S7.332 7.004 7.332 8.707l-.006 17.557c-.002 6.41 6.528 14.605 16.67 17.236c10.143-2.63 16.676-10.828 16.676-17.236");
}

</style>
