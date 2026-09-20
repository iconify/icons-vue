<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="gd__b6bln"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:battery-status-good-outline-sharp" /></template>
<style>
.gd__b6bln {
  fill: currentColor;
  d: path("M15.95 21.175L13.1 18.35l1.425-1.4l1.425 1.4l3.525-3.525l1.425 1.4zM7 22V4h3V2h4v2h3v8q-.525 0-1.025.088T15 12.35V6H9v14h2.35q.2.575.488 1.075t.687.925z");
}

</style>
