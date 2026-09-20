<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fm4k82bbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-48-regular" /></template>
<style>
.fm4k82bbn {
  fill: currentColor;
  d: path("M25.25 5.25a1.25 1.25 0 1 0-2.5 0v32.446L10.141 24.874a1.25 1.25 0 1 0-1.782 1.752l14.75 15a1.25 1.25 0 0 0 1.782 0l14.75-15a1.25 1.25 0 1 0-1.782-1.752L25.25 37.696z");
}

</style>
