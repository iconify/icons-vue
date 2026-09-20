<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="gks-mi0ef"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:folder-dotted" /></template>
<style>
.gks-mi0ef {
  fill: currentColor;
  d: path("M96 208a8 8 0 0 1-8 8H39.4A15.4 15.4 0 0 1 24 200.6V192a8 8 0 0 1 16 0v8h48a8 8 0 0 1 8 8Zm64-8h-32a8 8 0 0 0 0 16h32a8 8 0 0 0 0-16Zm64-56a8 8 0 0 0-8 8v48h-16a8 8 0 0 0 0 16h16.9a15.2 15.2 0 0 0 15.1-15.1V152a8 8 0 0 0-8-8Zm-8-72h-48a8 8 0 0 0 0 16h48v24a8 8 0 0 0 16 0V88a16 16 0 0 0-16-16ZM24 80V56a16 16 0 0 1 16-16h52.7a15.9 15.9 0 0 1 11.3 4.7l29.7 29.6a8.4 8.4 0 0 1 1.7 8.8A8 8 0 0 1 128 88H32a8 8 0 0 1-8-8Zm16-8h68.7l-16-16H40Zm-8 88a8 8 0 0 0 8-8v-32a8 8 0 0 0-16 0v32a8 8 0 0 0 8 8Z");
}

</style>
