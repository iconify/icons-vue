<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="n0mdosbdn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-exit-16-filled" /></template>
<style>
.n0mdosbdn {
  fill: currentColor;
  d: path("M4.25 1.5A2.75 2.75 0 0 0 1.5 4.25v7.5a2.75 2.75 0 0 0 2.75 2.75h6a.75.75 0 0 0 0-1.5h-6C3.56 13 3 12.44 3 11.75v-7.5C3 3.56 3.56 3 4.25 3h6a.75.75 0 0 0 0-1.5zm7.78 3.22a.75.75 0 1 0-1.06 1.06l1.47 1.47H6.75a.75.75 0 0 0 0 1.5h5.69l-1.47 1.47a.75.75 0 1 0 1.06 1.06l2.75-2.75a.75.75 0 0 0 0-1.06z");
}

</style>
