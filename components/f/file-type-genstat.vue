<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="h5p9x7edi"/><path class="avaboxb8b"/><path class="s0h5_lbuh"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-genstat" /></template>
<style>
.avaboxb8b {
  fill: var(--svg-color--6cc1ee, #6cc1ee);
  d: path("M2 2h28v21.613c-9.333.915-12.5-17.32-17.956-17.32C7.455 6.293 5.7 16.57 2 17.787Z");
}

.h5p9x7edi {
  fill: var(--svg-color--e2e2e2, #e2e2e2);
  d: path("M2 5.861h28v20H2z");
}

.s0h5_lbuh {
  fill: var(--svg-color--46b270, #46b270);
  d: path("M2 30h28v-4.639C20.382 26.388 15.526 8.083 11.959 8.042c-3.167 0-4.9 10.382-9.959 11.494Z");
}

</style>
