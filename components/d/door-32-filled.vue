<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="t_h97rt_v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:door-32-filled" /></template>
<style>
.t_h97rt_v {
  fill: currentColor;
  d: path("M23.75 2A3.25 3.25 0 0 1 27 5.25v21.5A3.25 3.25 0 0 1 23.75 30H8.25a3.25 3.25 0 0 1-3.246-3.083L5 26.75V5.25A3.25 3.25 0 0 1 8.25 2zM10.5 13.75a1.75 1.75 0 1 0 0 3.5a1.75 1.75 0 0 0 0-3.5");
}

</style>
