<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="likisnb1x"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-turn-right-left-20-regular" /></template>
<style>
.likisnb1x {
  fill: currentColor;
  d: path("M4.004 14.566a.5.5 0 0 0 .31.4l5 1.998a.5.5 0 1 0 .372-.928L5.848 14.5l11.524-4.59c.828-.329.844-1.495.025-1.847L5.697 3.04a.5.5 0 0 0-.394.919l11.7 5.023L5.534 13.55l1.912-3.826a.5.5 0 1 0-.894-.447l-2.49 4.982a.5.5 0 0 0-.059.307");
}

</style>
