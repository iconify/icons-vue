<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="kcbd0lb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-closed-16-regular" /></template>
<style>
.kcbd0lb0f {
  fill: currentColor;
  d: path("M8 1a3 3 0 0 1 3 3v2a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2V4a3 3 0 0 1 3-3M5 7a1 1 0 0 0-1 1v5a1 1 0 0 0 1 1h6a1 1 0 0 0 1-1V8a1 1 0 0 0-1-1zm3 2.5a1 1 0 1 1 0 2a1 1 0 0 1 0-2M8 2a2 2 0 0 0-2 2v2h4V4a2 2 0 0 0-2-2");
}

</style>
