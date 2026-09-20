<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="s81op-8eq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-forward-16-filled" /></template>
<style>
.s81op-8eq {
  fill: currentColor;
  d: path("M9.22 4.28a.75.75 0 0 1 1.06-1.06l3.5 3.5a.75.75 0 0 1 0 1.06l-3.5 3.5a.75.75 0 1 1-1.06-1.06L11.44 8H7.75a4.25 4.25 0 0 0-4.25 4.25a.75.75 0 0 1-1.5 0A5.75 5.75 0 0 1 7.75 6.5h3.69z");
}

</style>
