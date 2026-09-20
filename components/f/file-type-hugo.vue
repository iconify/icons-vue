<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="bqvqogb6i"/><path class="o4wiiobeh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-hugo" /></template>
<style>
.bqvqogb6i {
  fill: var(--svg-color--ff4088, #ff4088);
  stroke: var(--svg-color--c9177e, #c9177e);
  stroke-width: var(--svg-stroke-width--2px, 2px);
  d: path("m17.64 3.37l8.3 4.84a3.2 3.2 0 0 1 1.6 2.76v9.91c0 1.26-.68 2.42-1.78 3.04l-8.25 4.64c-1.1.62-2.43.61-3.52-.01l-7.6-4.38a3.85 3.85 0 0 1-1.93-3.33v-9.4a4 4 0 0 1 1.9-3.4l7.47-4.62c1.36-.5 2.77-.62 3.8-.05z");
}

.o4wiiobeh {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.26 23.37v-15h3.13v5.47h5.2V8.38h3.15v15H18.6v-6.56h-5.2v6.55z");
}

</style>
