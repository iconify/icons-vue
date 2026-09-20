<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="uh3o6d06a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:collections-empty-16-filled" /></template>
<style>
.uh3o6d06a {
  fill: currentColor;
  d: path("M2.854 2.121a2.5 2.5 0 0 0-1.768 3.062L2.12 9.047A2.5 2.5 0 0 0 5 10.857V8a3 3 0 0 1 3-3h2.354L9.78 2.854a2.5 2.5 0 0 0-3.062-1.768zM6 8a2 2 0 0 1 2-2h5a2 2 0 0 1 2 2v5a2 2 0 0 1-2 2H8a2 2 0 0 1-2-2z");
}

</style>
