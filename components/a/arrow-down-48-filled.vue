<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j3j8cm8vw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-48-filled" /></template>
<style>
.j3j8cm8vw {
  fill: currentColor;
  d: path("M25.5 5.25a1.5 1.5 0 0 0-3 0v31.835L10.32 24.698a1.5 1.5 0 1 0-2.14 2.104l14.75 15l.031.03c.27.259.636.418 1.039.418a1.5 1.5 0 0 0 1.07-.448l14.75-15a1.5 1.5 0 1 0-2.14-2.104L25.5 37.085z");
}

</style>
