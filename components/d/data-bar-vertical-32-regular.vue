<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="o-fsell9t"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:data-bar-vertical-32-regular" /></template>
<style>
.o-fsell9t {
  fill: currentColor;
  d: path("M7.5 3A3.5 3.5 0 0 1 11 6.5v19a3.5 3.5 0 1 1-7 0v-19A3.5 3.5 0 0 1 7.5 3m9 6a3.5 3.5 0 0 1 3.5 3.5v13a3.5 3.5 0 1 1-7 0v-13A3.5 3.5 0 0 1 16.5 9m9 6a3.5 3.5 0 0 1 3.5 3.5v7a3.5 3.5 0 1 1-7 0v-7a3.5 3.5 0 0 1 3.5-3.5M7.5 5A1.5 1.5 0 0 0 6 6.5v19a1.5 1.5 0 0 0 3 0v-19A1.5 1.5 0 0 0 7.5 5m9 6a1.5 1.5 0 0 0-1.5 1.5v13a1.5 1.5 0 0 0 3 0v-13a1.5 1.5 0 0 0-1.5-1.5m9 6a1.5 1.5 0 0 0-1.5 1.5v7a1.5 1.5 0 0 0 3 0v-7a1.5 1.5 0 0 0-1.5-1.5");
}

</style>
