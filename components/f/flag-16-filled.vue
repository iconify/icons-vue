<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n3p-njbrw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:flag-16-filled" /></template>
<style>
.n3p-njbrw {
  fill: currentColor;
  d: path("M4 10h9a.5.5 0 0 0 .407-.79L11.114 6l2.293-3.21A.5.5 0 0 0 13 2H3.5a.5.5 0 0 0-.5.5v11a.5.5 0 0 0 1 0z");
}

</style>
