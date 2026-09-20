<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="c55a9jf2o"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:diamond-12-regular" /></template>
<style>
.c55a9jf2o {
  fill: currentColor;
  d: path("M4.586 1.086a2 2 0 0 1 2.828 0l3.5 3.5a2 2 0 0 1 0 2.828l-3.5 3.499a2 2 0 0 1-2.828 0l-3.5-3.5a2 2 0 0 1 0-2.827zm2.121.707a1 1 0 0 0-1.414 0l-3.5 3.5a1 1 0 0 0 0 1.414l3.5 3.499a1 1 0 0 0 1.414 0l3.5-3.5a1 1 0 0 0 0-1.413z");
}

</style>
