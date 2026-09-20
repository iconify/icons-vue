<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="cioxk4bpu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-maximize-48-filled" /></template>
<style>
.cioxk4bpu {
  fill: currentColor;
  d: path("M39 7.5A1.5 1.5 0 0 1 40.5 9v15.5a1.5 1.5 0 0 1-3 0V12.621L12.621 37.5H24.5a1.5 1.5 0 0 1 0 3H9A1.5 1.5 0 0 1 7.5 39V23.5a1.5 1.5 0 0 1 3 0v11.879L35.379 10.5H23.5a1.5 1.5 0 0 1 0-3z");
}

</style>
