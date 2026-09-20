<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ejdx8cc5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-light-behat" /></template>
<style>
.ejdx8cc5k {
  fill: var(--svg-color--4a4a4a, #4a4a4a);
  d: path("M5.44 11a9 9 0 0 1 15.17-6.55a8 8 0 0 1 2.1 3q.72 1.65.73 3.55a9 9 0 0 1-.96 3.8a5 5 0 0 1-.83 1.2c2.84 1.5 4.91 4.92 4.91 8.51a9.4 9.4 0 0 1-1.6 5.49h-2.64a8.4 8.4 0 0 0 1.99-5.44c0-4.3-3.15-7.44-7.38-8.41l-1.34-.34l-2.32-.58a4.47 4.47 0 1 1 2.17-8.68a4.47 4.47 0 0 1 2.42 7.15l-.93-.7l.78 2.86l2.98-.04l-.82-.61a7 7 0 0 0-3.82-11.1a6.99 6.99 0 0 0-4.6 13.16a8.47 8.47 0 0 0-3.3 10.99l-1.3.72l3.87.6l1.55-3.6l-1.49.82A5.5 5.5 0 1 1 16.5 30H5.44z");
}

</style>
