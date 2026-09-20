<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="rklg7vb0c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:crop-portrait-sharp" /></template>
<style>
.rklg7vb0c {
  fill: currentColor;
  d: path("M4 22V2h16v20z");
}

</style>
