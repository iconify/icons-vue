<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="iguhrdb5n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:dock-to-left-outline-sharp" /></template>
<style>
.iguhrdb5n {
  fill: currentColor;
  d: path("M16 19h3V5h-3zM5 19h10V5H5zm11 0h3zM4 20V4h16v16z");
}

</style>
