<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vesim01fz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:dual-screen-vertical-scroll-20-regular" /></template>
<style>
.vesim01fz {
  fill: currentColor;
  d: path("M4 4a2 2 0 0 0-2 2v8a2 2 0 0 0 2 2h12a2 2 0 0 0 2-2V6a2 2 0 0 0-2-2zM3 6a1 1 0 0 1 1-1h5.5v10H4a1 1 0 0 1-1-1zm7.5 9V5H16a1 1 0 0 1 1 1v8a1 1 0 0 1-1 1zm5.354-3.854a.5.5 0 0 1 0 .708l-2 2a.5.5 0 0 1-.708 0l-2-2a.5.5 0 0 1 .708-.708l1.646 1.647l1.646-1.647a.5.5 0 0 1 .708 0m0-3a.5.5 0 0 1-.708.708L13.5 7.207l-1.646 1.647a.5.5 0 0 1-.708-.708l2-2a.5.5 0 0 1 .708 0z");
}

</style>
