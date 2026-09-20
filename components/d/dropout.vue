<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ro60a8b-h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:dropout" /></template>
<style>
.ro60a8b-h {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.1 40.906V7.094h5.494C34.892 7.094 42.5 14.702 42.5 24s-7.608 16.906-16.906 16.906zM5.5 26.95h9.241v9.241H5.5zm0-15.967h9.241v9.241H5.5z");
}

</style>
