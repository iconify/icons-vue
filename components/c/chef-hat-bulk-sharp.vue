<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x-0l70oxd"/><path class="qdv2kgz8m"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chef-hat-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.qdv2kgz8m {
  d: path("M6 16h12a1 1 0 0 1 0 2H6a1 1 0 0 1 0-2");
}

.x-0l70oxd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M7.107 5.963a5.001 5.001 0 0 1 9.786 0a4.94 4.94 0 0 1 2.735.971c.955.718 1.622 1.776 1.911 2.931c.582 2.332-.391 4.666-2.539 5.783V21a1 1 0 0 1-1 1H6a1 1 0 0 1-1-1v-5.352c-2.148-1.117-3.121-3.451-2.539-5.783c.289-1.155.956-2.213 1.911-2.931a4.94 4.94 0 0 1 2.735-.971");
}

</style>
