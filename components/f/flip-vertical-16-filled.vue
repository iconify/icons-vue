<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="xiev0lbjc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flip-vertical-16-filled" /></template>
<style>
.xiev0lbjc {
  fill: currentColor;
  d: path("M12.651 1.116a.75.75 0 0 1 .35.634v4.5a.75.75 0 0 1-.75.75h-9.5a.75.75 0 0 1-.322-1.428l9.5-4.5a.75.75 0 0 1 .722.044M6.085 5.5H11.5V2.935zm6.915 9a.5.5 0 0 1-.724.447l-10-5A.5.5 0 0 1 2.5 9h10a.5.5 0 0 1 .5.5z");
}

</style>
