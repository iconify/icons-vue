<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="y8pmc0tmr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-ripple" /></template>
<style>
.y8pmc0tmr {
  fill: var(--svg-color--3e95ff, #3e95ff);
  d: path("M24.78 16.22A9 9 0 0 0 9.83 9.51a2.4 2.4 0 0 1-3.2-3.6A13.81 13.81 0 0 1 29.6 16.22a13.7 13.7 0 0 1-2.19 7.46l1.87 1.76a2.4 2.4 0 0 1-3.3 3.5l-3.45-3.25a2.4 2.4 0 0 1-.12-3.39a9 9 0 0 0 2.38-6.08M2 16.22a2.4 2.4 0 1 1 4.82 0a9 9 0 0 0 4.15 7.58a2.4 2.4 0 1 1-2.6 4.05A13.8 13.8 0 0 1 2 16.22m13.8 4.18a4.17 4.17 0 1 0 0-8.35a4.17 4.17 0 0 0 0 8.34");
}

</style>
