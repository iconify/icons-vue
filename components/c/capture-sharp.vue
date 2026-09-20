<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="lsr9ewboa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:capture-sharp" /></template>
<style>
.lsr9ewboa {
  fill: currentColor;
  d: path("M6 16h12V8H6zm-4 4V4h20v16z");
}

</style>
