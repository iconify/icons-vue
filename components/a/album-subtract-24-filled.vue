<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="fet3yj0pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:album-subtract-24-filled" /></template>
<style>
.fet3yj0pj {
  fill: currentColor;
  d: path("M6.5 12a5.5 5.5 0 1 1 0 11a5.5 5.5 0 0 1 0-11M20 4a2 2 0 0 1 2 2v12a2 2 0 0 1-2 2h-7.498A6.5 6.5 0 0 0 6.5 11V4zM3.495 17a.5.5 0 0 0 0 1h6.002a.5.5 0 0 0 0-1zM5 11.174a6.5 6.5 0 0 0-3 1.636V6a2 2 0 0 1 2-2h1zM12 7a2 2 0 0 0-2 2v1a2 2 0 0 0 2 2h4a2 2 0 0 0 2-2V9a2 2 0 0 0-2-2zm4 1.5a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-4a.5.5 0 0 1-.5-.5V9a.5.5 0 0 1 .5-.5z");
}

</style>
