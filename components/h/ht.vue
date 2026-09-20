<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="y5fn_nbnk"/><path class="yh5i1r52j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ht" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.y5fn_nbnk {
  fill: var(--svg-color--e6eefa, #e6eefa);
  d: path("M13.895 8.54c0-2.585-1.238-4.807-2.179-5.53c-.004-.003-.073-.042-.066.061l-.002.003c-.079 4.99-2.585 6.343-3.963 8.165c-3.18 4.204-.222 8.813 2.79 9.665c1.684.477-.39-.843-.657-3.631c-.323-3.37 4.077-5.943 4.077-8.733");
}

.yh5i1r52j {
  fill: var(--svg-color--2ea7df, #2ea7df);
  d: path("M15.537 10.118c-.019-.014-.046-.023-.065.01c-.052.634-.68 1.993-1.476 3.241c-2.7 4.232-1.161 6.272-.296 7.368c.503.636 0 0 1.256-.65c.098-.051 2.45-1.413 2.704-4.518c.247-3.006-1.5-4.9-2.123-5.451");
}

</style>
