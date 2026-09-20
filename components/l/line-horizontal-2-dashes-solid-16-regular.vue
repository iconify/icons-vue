<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="durhuiblv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-horizontal-2-dashes-solid-16-regular" /></template>
<style>
.durhuiblv {
  fill: currentColor;
  d: path("M2.5 5a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zM7 5a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zm4.5 0a.5.5 0 0 0 0 1h2a.5.5 0 0 0 0-1zm-9 5a.5.5 0 0 0 0 1h11a.5.5 0 0 0 0-1z");
}

</style>
