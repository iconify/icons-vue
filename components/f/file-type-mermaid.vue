<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="ivzshm1nf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-mermaid" /></template>
<style>
.ivzshm1nf {
  fill: var(--svg-color--fd366e, #fd366e);
  d: path("M29.973 4.478A14.24 14.24 0 0 0 16 13.842c-2.107-5.82-7.787-9.628-13.973-9.364a14.25 14.25 0 0 0 6.2 12.36a7.65 7.65 0 0 1 3.316 6.32v4.376h8.916V23.16a7.65 7.65 0 0 1 3.315-6.32a14.25 14.25 0 0 0 6.2-12.36z");
}

</style>
