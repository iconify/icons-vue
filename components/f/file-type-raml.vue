<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="md48awbbo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-raml" /></template>
<style>
.md48awbbo {
  fill: var(--svg-color--73cfee, #73cfee);
  d: path("M19.24 2H4.063l1.514 2.429h13.577A6.1 6.1 0 0 1 23.55 6.3a6.37 6.37 0 0 1 1.818 4.469a5.93 5.93 0 0 1-1.786 4.295a7.54 7.54 0 0 1-4.369 2.048h-1.662l-4.583-.037l1.323 2.291H16.3l.109.175h.016l5.917 9.99l.027.046l.038.038a1.335 1.335 0 0 0 2.272-.944a.72.72 0 0 0-.206-.543a1.5 1.5 0 0 1-.189-.263l-4.891-8.325a8.6 8.6 0 0 0 6-2.562A8.8 8.8 0 0 0 19.24 2");
}

</style>
