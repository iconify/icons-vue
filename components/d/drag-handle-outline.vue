<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="g3dyevngv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:drag-handle-outline" /></template>
<style>
.g3dyevngv {
  fill: currentColor;
  d: path("M4 15v-2h16v2zm0-4V9h16v2z");
}

</style>
