<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":28,"height":28};
const content = `<path class="r4-_9pz6a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:archive-28-filled" /></template>
<style>
.r4-_9pz6a {
  fill: currentColor;
  d: path("M3 4.5A1.5 1.5 0 0 1 4.5 3h19A1.5 1.5 0 0 1 25 4.5v2A1.5 1.5 0 0 1 23.5 8h-19A1.5 1.5 0 0 1 3 6.5zm1 5h20v10.75A4.75 4.75 0 0 1 19.25 25H8.75A4.75 4.75 0 0 1 4 20.25zm7.75 3a.75.75 0 0 0 0 1.5h4.5a.75.75 0 0 0 0-1.5z");
}

</style>
