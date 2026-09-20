<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u9lgkbyee"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dual-screen-group-20-regular" /></template>
<style>
.u9lgkbyee {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2zM3 6a1 1 0 0 1 1-1h5.5v10H4a1 1 0 0 1-1-1zm7.5 9V5H16a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1z");
}

</style>
