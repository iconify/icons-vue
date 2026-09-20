<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ak-18k5pj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:align-bottom-32-filled" /></template>
<style>
.ak-18k5pj {
  fill: currentColor;
  d: path("M4 29a1 1 0 1 1 0-2h24a1 1 0 1 1 0 2zm1-7.5A3.5 3.5 0 0 0 8.5 25h3a3.5 3.5 0 0 0 3.5-3.5v-15A3.5 3.5 0 0 0 11.5 3h-3A3.5 3.5 0 0 0 5 6.5zm12 0a3.5 3.5 0 0 0 3.5 3.5h3a3.5 3.5 0 0 0 3.5-3.5v-9A3.5 3.5 0 0 0 23.5 9h-3a3.5 3.5 0 0 0-3.5 3.5z");
}

</style>
