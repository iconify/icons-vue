<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<path class="vwdd4mhye"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:branch-fork-link-20-filled" /></template>
<style>
.vwdd4mhye {
  fill: currentColor;
  d: path("M5.5 7.959a3 3 0 1 0-1 0v4.082a3 3 0 1 0 1 0V11H11a2.5 2.5 0 0 0 2.5-2.5v-.541a3 3 0 1 0-1 0V8.5A1.5 1.5 0 0 1 11 10H5.5zm7 5.041a2.5 2.5 0 0 0 0 5h.5a.5.5 0 0 0 0-1h-.5a1.5 1.5 0 0 1 0-3h.5a.5.5 0 0 0 0-1zm3.5 0a.5.5 0 0 0 0 1h.5a1.5 1.5 0 0 1 0 3H16a.5.5 0 0 0 0 1h.5a2.5 2.5 0 0 0 0-5zm-4 2.5a.5.5 0 0 1 .5-.5h4a.5.5 0 0 1 0 1h-4a.5.5 0 0 1-.5-.5");
}

</style>
