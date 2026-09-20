<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vehhl8bju"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:games-20-regular" /></template>
<style>
.vehhl8bju {
  fill: currentColor;
  d: path("M6 7.5a.5.5 0 0 1 1 0V9h1.5a.5.5 0 0 1 0 1H7v1.5a.5.5 0 0 1-1 0V10H4.5a.5.5 0 0 1 0-1H6zm9 .5a1 1 0 1 1-2 0a1 1 0 0 1 2 0m-3 4a1 1 0 1 0 0-2a1 1 0 0 0 0 2M2 9.5A5.5 5.5 0 0 1 7.5 4h5a5.5 5.5 0 1 1 0 11h-5A5.5 5.5 0 0 1 2 9.5M7.5 5a4.5 4.5 0 0 0 0 9h5a4.5 4.5 0 1 0 0-9z");
}

</style>
