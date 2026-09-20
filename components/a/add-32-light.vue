<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="rlwbb2btz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:add-32-light" /></template>
<style>
.rlwbb2btz {
  fill: currentColor;
  d: path("M16.5 3.5a.5.5 0 0 0-1 0v12h-12a.5.5 0 0 0 0 1h12v12a.5.5 0 0 0 1 0v-12h12a.5.5 0 0 0 0-1h-12z");
}

</style>
