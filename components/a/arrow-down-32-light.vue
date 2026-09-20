<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="a6n029bac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="fluent:arrow-down-32-light" /></template>
<style>
.a6n029bac {
  fill: currentColor;
  d: path("M16.5 3.5a.5.5 0 0 0-1 0v23.833l-9.655-9.195a.5.5 0 0 0-.69.724l10.5 10a.5.5 0 0 0 .69 0l10.5-10a.5.5 0 0 0-.69-.724L16.5 27.333z");
}

</style>
