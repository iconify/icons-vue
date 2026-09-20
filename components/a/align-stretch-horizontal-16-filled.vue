<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="blb4sacys"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-stretch-horizontal-16-filled" /></template>
<style>
.blb4sacys {
  fill: currentColor;
  d: path("M3 1.5a.5.5 0 0 0-1 0v13a.5.5 0 0 0 1 0zm11 0a.5.5 0 0 0-1 0v13a.5.5 0 0 0 1 0zm-10 3A1.5 1.5 0 0 1 5.5 3h5A1.5 1.5 0 0 1 12 4.5v1A1.5 1.5 0 0 1 10.5 7h-5A1.5 1.5 0 0 1 4 5.5zm0 6A1.5 1.5 0 0 1 5.5 9h5a1.5 1.5 0 0 1 1.5 1.5v1a1.5 1.5 0 0 1-1.5 1.5h-5A1.5 1.5 0 0 1 4 11.5z");
}

</style>
