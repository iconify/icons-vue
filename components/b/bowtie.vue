<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":250};
const content = `<path class="mxu0u0tqf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:bowtie" /></template>
<style>
.mxu0u0tqf {
  d: path("M256 0L128.001 106.493L0 0v249.817l128.001-106.492L256 249.817V0zM150.135 124.908l77.552-64.521v129.042l-77.552-64.521zM28.313 60.387l77.553 64.521l-77.553 64.521V60.387z");
  fill: var(--svg-color--333, #333);
}

</style>
