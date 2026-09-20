<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="u_iloebhf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-export-up-20-filled" /></template>
<style>
.u_iloebhf {
  fill: currentColor;
  d: path("M10.53 1.72a.75.75 0 0 0-1.06 0l-4 4a.75.75 0 0 0 1.06 1.06l2.72-2.72v10.19a.75.75 0 0 0 1.5 0V4.06l2.72 2.72a.75.75 0 1 0 1.06-1.06zM4.5 16.5a.75.75 0 0 0 0 1.5h11a.75.75 0 0 0 0-1.5z");
}

</style>
