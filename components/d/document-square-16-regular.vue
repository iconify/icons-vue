<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":16,"height":16};
const content = `<path class="qi84dhbaf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:document-square-16-regular" /></template>
<style>
.qi84dhbaf {
  fill: currentColor;
  d: path("M9.482 2c.464 0 .91.185 1.238.513l2.767 2.767c.328.328.513.774.513 1.238v5.732A1.75 1.75 0 0 1 12.25 14h-8.5A1.75 1.75 0 0 1 2 12.25v-8.5C2 2.784 2.784 2 3.75 2zM3.75 3a.75.75 0 0 0-.75.75v8.5c0 .414.336.75.75.75h8.5a.75.75 0 0 0 .75-.75V7h-2.5A1.5 1.5 0 0 1 9 5.5V3zM10 5.5a.5.5 0 0 0 .5.5h2.291l-.01-.013l-2.768-2.767L10 3.209z");
}

</style>
