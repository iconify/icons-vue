<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fdlyq8b8l"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:archive-48-regular" /></template>
<style>
.fdlyq8b8l {
  fill: currentColor;
  d: path("M37.75 6A4.25 4.25 0 0 1 42 10.25v3.5c0 1.52-.8 2.853-2 3.605V35.75A6.25 6.25 0 0 1 33.75 42h-19.5A6.25 6.25 0 0 1 8 35.75V17.355c-1.2-.752-2-2.084-2-3.605v-3.5A4.25 4.25 0 0 1 10.25 6zM10.5 35.75a3.75 3.75 0 0 0 3.75 3.75h19.5a3.75 3.75 0 0 0 3.75-3.75V18h-27zM27.75 22a1.25 1.25 0 1 1 0 2.5h-7.5a1.25 1.25 0 1 1 0-2.5zM10.25 8.5a1.75 1.75 0 0 0-1.75 1.75v3.5c0 .966.784 1.75 1.75 1.75h27.5a1.75 1.75 0 0 0 1.75-1.75v-3.5a1.75 1.75 0 0 0-1.75-1.75z");
}

</style>
