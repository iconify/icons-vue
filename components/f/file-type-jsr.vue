<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="wdeij7bfj"/><path class="sogpq3b2s"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-jsr" /></template>
<style>
.sogpq3b2s {
  fill: var(--svg-color--f7df1e, #f7df1e);
  d: path("M4.15 14.92h2.16v2.16h2.15v-6.46h2.16v8.61H4.15m8.62-8.61h6.46v2.15h-4.3v2.15h4.3v6.46h-6.46v-2.15h4.3v-2.15h-4.3m8.61-4.31h6.47v4.3h-2.16v-2.15h-2.15v6.46h-2.16");
}

.wdeij7bfj {
  fill: var(--svg-color--083344, #083344);
  d: path("M2 12.77h4.3v-4.3h15.08v2.15H30v8.61h-4.3v4.3H10.61v-2.15H2");
}

</style>
