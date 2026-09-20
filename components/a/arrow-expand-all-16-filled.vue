<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="q-l9gdxld"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-expand-all-16-filled" /></template>
<style>
.q-l9gdxld {
  fill: currentColor;
  d: path("M1 3.75A.75.75 0 0 1 1.75 3h12.5a.75.75 0 0 1 0 1.5H1.75A.75.75 0 0 1 1 3.75m7 3A.75.75 0 0 1 8.75 6h5.5a.75.75 0 0 1 0 1.5h-5.5A.75.75 0 0 1 8 6.75m-1.22 5.03l-2 2a.75.75 0 0 1-1.06 0l-2-2a.75.75 0 1 1 1.06-1.06l.72.72V6.75a.75.75 0 0 1 1.5 0v4.69l.72-.72a.75.75 0 0 1 1.06 1.06");
}

</style>
