<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="egtggdcut"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:heart-circle-16-regular" /></template>
<style>
.egtggdcut {
  fill: currentColor;
  d: path("m8 7l-.421-.492a1.465 1.465 0 1 0-2.157 1.98l2.4 2.44c.098.1.259.1.357 0l2.4-2.44a1.465 1.465 0 1 0-2.157-1.98zM2 8a6 6 0 1 1 12 0A6 6 0 0 1 2 8m6-5a5 5 0 1 0 0 10A5 5 0 0 0 8 3");
}

</style>
