<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="v5woy9bnp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols:electric-bolt-rounded" /></template>
<style>
.v5woy9bnp {
  fill: currentColor;
  d: path("m11 14.5l-5.925-.75q-.625-.075-.813-.675t.263-1.025l10.225-9.8q.125-.125.3-.187T15.525 2q.5 0 .763.425t.012.875L13 9.5l5.925.75q.625.075.813.675t-.263 1.025L9.25 21.75q-.125.125-.3.188T8.475 22q-.5 0-.763-.425T7.7 20.7z");
}

</style>
