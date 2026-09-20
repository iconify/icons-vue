<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="nmec7tb6n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:glance-default-12-filled" /></template>
<style>
.nmec7tb6n {
  fill: currentColor;
  d: path("M6 9.5A1.5 1.5 0 0 0 7.5 11h2A1.5 1.5 0 0 0 11 9.5v-3A1.5 1.5 0 0 0 9.5 5h-2A1.5 1.5 0 0 0 6 6.5zm-5-4A1.5 1.5 0 0 0 2.5 7h1A1.5 1.5 0 0 0 5 5.5v-3A1.5 1.5 0 0 0 3.5 1h-1A1.5 1.5 0 0 0 1 2.5zM7.5 4a1.5 1.5 0 1 1 0-3h2a1.5 1.5 0 0 1 0 3zM1 9.5A1.5 1.5 0 0 0 2.5 11h1a1.5 1.5 0 0 0 0-3h-1A1.5 1.5 0 0 0 1 9.5");
}

</style>
