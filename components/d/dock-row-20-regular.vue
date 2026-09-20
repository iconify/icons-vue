<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vdkbtbc6g"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dock-row-20-regular" /></template>
<style>
.vdkbtbc6g {
  fill: currentColor;
  d: path("M3 4a1.5 1.5 0 0 0-1.5 1.5v2A1.5 1.5 0 0 0 3 9h2a1.5 1.5 0 0 0 1.5-1.5v-2A1.5 1.5 0 0 0 5 4zm-.5 1.5A.5.5 0 0 1 3 5h2a.5.5 0 0 1 .5.5v2A.5.5 0 0 1 5 8H3a.5.5 0 0 1-.5-.5zM3 10a1.5 1.5 0 0 0-1.5 1.5v2A1.5 1.5 0 0 0 3 15h2a1.5 1.5 0 0 0 1.5-1.5v-2A1.5 1.5 0 0 0 5 10zm-.5 1.5A.5.5 0 0 1 3 11h2a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.5.5H3a.5.5 0 0 1-.5-.5zm5-6A1.5 1.5 0 0 1 9 4h2a1.5 1.5 0 0 1 1.5 1.5v2A1.5 1.5 0 0 1 11 9H9a1.5 1.5 0 0 1-1.5-1.5zM9 5a.5.5 0 0 0-.5.5v2A.5.5 0 0 0 9 8h2a.5.5 0 0 0 .5-.5v-2A.5.5 0 0 0 11 5zm0 5a1.5 1.5 0 0 0-1.5 1.5v2A1.5 1.5 0 0 0 9 15h2a1.5 1.5 0 0 0 1.5-1.5v-2A1.5 1.5 0 0 0 11 10zm-.5 1.5A.5.5 0 0 1 9 11h2a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.5.5H9a.5.5 0 0 1-.5-.5zm5-6A1.5 1.5 0 0 1 15 4h2a1.5 1.5 0 0 1 1.5 1.5v2A1.5 1.5 0 0 1 17 9h-2a1.5 1.5 0 0 1-1.5-1.5zM15 5a.5.5 0 0 0-.5.5v2a.5.5 0 0 0 .5.5h2a.5.5 0 0 0 .5-.5v-2A.5.5 0 0 0 17 5zm0 5a1.5 1.5 0 0 0-1.5 1.5v2A1.5 1.5 0 0 0 15 15h2a1.5 1.5 0 0 0 1.5-1.5v-2A1.5 1.5 0 0 0 17 10zm-.5 1.5a.5.5 0 0 1 .5-.5h2a.5.5 0 0 1 .5.5v2a.5.5 0 0 1-.5.5h-2a.5.5 0 0 1-.5-.5z");
}

</style>
