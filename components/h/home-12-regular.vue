<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":12,"height":12};
const content = `<path class="mdgfq-b4f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:home-12-regular" /></template>
<style>
.mdgfq-b4f {
  fill: currentColor;
  d: path("M5.37 1.222a1 1 0 0 1 1.26 0l3.814 3.09A1.5 1.5 0 0 1 11 5.476V10a1 1 0 0 1-1 1H8a1 1 0 0 1-1-1V7H5v3a1 1 0 0 1-1 1H2a1 1 0 0 1-1-1V5.477a1.5 1.5 0 0 1 .556-1.166zm4.445 3.866L6 2L2.185 5.088A.5.5 0 0 0 2 5.477V10h2V7a1 1 0 0 1 1-1h2a1 1 0 0 1 1 1v3h2V5.477a.5.5 0 0 0-.185-.389");
}

</style>
