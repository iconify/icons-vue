<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="c3rr40baj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:error-circle-48-filled" /></template>
<style>
.c3rr40baj {
  fill: currentColor;
  d: path("M24 4C12.954 4 4 12.954 4 24s8.954 20 20 20s20-8.954 20-20S35.046 4 24 4m0 9c.69 0 1.25.56 1.25 1.25v12.5a1.25 1.25 0 1 1-2.5 0v-12.5c0-.69.56-1.25 1.25-1.25m0 21a2 2 0 1 1 0-4a2 2 0 0 1 0 4");
}

</style>
