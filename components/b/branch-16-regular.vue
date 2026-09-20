<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="tig0web7s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:branch-16-regular" /></template>
<style>
.tig0web7s {
  fill: currentColor;
  d: path("M11.5 6a2.5 2.5 0 0 0-2.446 1.985C7.172 7.86 5.466 6.963 5.081 5.931a2.5 2.5 0 1 0-1.08.019v4.1a2.5 2.5 0 1 0 1 0V7.466a7 7 0 0 0 4.047 1.52A2.5 2.5 0 1 0 11.5 6M3 3.5a1.5 1.5 0 1 1 3 0a1.5 1.5 0 0 1-3 0m3 9a1.5 1.5 0 1 1-2.999 0a1.5 1.5 0 0 1 3 0m5.5-2.5a1.5 1.5 0 1 1 0-3a1.5 1.5 0 0 1 0 3");
}

</style>
