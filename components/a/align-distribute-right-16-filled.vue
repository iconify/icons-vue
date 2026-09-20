<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="u1psh1k0e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-distribute-right-16-filled" /></template>
<style>
.u1psh1k0e {
  fill: currentColor;
  d: path("M15 1.5a.5.5 0 0 0-1 0v13a.5.5 0 0 0 1 0zm-7 0a.5.5 0 0 0-1 0v13a.5.5 0 0 0 1 0zM3.5 13A1.5 1.5 0 0 1 2 11.5v-7A1.5 1.5 0 0 1 3.5 3h1A1.5 1.5 0 0 1 6 4.5v7A1.5 1.5 0 0 1 4.5 13zM9 9.5a1.5 1.5 0 0 0 1.5 1.5h1A1.5 1.5 0 0 0 13 9.5v-3A1.5 1.5 0 0 0 11.5 5h-1A1.5 1.5 0 0 0 9 6.5z");
}

</style>
