<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="j-05twbww"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:lock-open-16-filled" /></template>
<style>
.j-05twbww {
  fill: currentColor;
  d: path("M12 1a3 3 0 0 1 3 3v.5a.5.5 0 0 1-1 0V4a2 2 0 1 0-4 0v2h1a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V8a2 2 0 0 1 2-2h4V4a3 3 0 0 1 3-3M8 9.5a1 1 0 1 0 0 2a1 1 0 0 0 0-2");
}

</style>
