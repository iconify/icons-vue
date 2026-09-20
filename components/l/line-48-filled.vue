<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j9lo0vple"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:line-48-filled" /></template>
<style>
.j9lo0vple {
  fill: currentColor;
  d: path("M43.56 4.44a1.5 1.5 0 0 1 0 2.12l-37 37a1.5 1.5 0 0 1-2.12-2.12l37-37a1.5 1.5 0 0 1 2.12 0");
}

</style>
