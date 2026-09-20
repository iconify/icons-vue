<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="vs2qnkbxc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:left-panel-close-outline-sharp" /></template>
<style>
.vs2qnkbxc {
  fill: currentColor;
  d: path("M16.5 16V8l-4 4zM5 19h3V5H5zm5 0h9V5h-9zm-2 0H5zm-5 2V3h18v18z");
}

</style>
