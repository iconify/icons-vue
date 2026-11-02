<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="kjb8kxr-y"/><path class="rf0verbnp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:group-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kjb8kxr-y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6 10V9a3 3 0 0 1 3-3h3a3 3 0 0 1 3 3v2a3 3 0 0 1 3 3v1a3 3 0 0 1-3 3h-3a3 3 0 0 1-3-3v-2a3 3 0 0 1-3-3");
}

.rf0verbnp {
  d: path("M2 6c0-1.065.416-2.078 1.172-2.828a3.9 3.9 0 0 1 1.271-.857A4 4 0 0 1 6 2a1 1 0 0 1 0 2c-.534 0-1.039.206-1.414.586c-.378.378-.589.88-.586 1.414a1 1 0 0 1-2 0m18.828-2.828A3.96 3.96 0 0 1 22 6a1 1 0 0 1-2 0a2 2 0 0 0-2-2a1 1 0 0 1 0-2c1.067 0 2.077.414 2.828 1.172M5.4 21.956a3.98 3.98 0 0 1-2.228-1.128A3.97 3.97 0 0 1 2 18a1 1 0 0 1 2 0c0 .534.206 1.039.586 1.414c.377.378.88.589 1.414.586a1 1 0 0 1 0 2q-.302 0-.6-.044m15.428-1.128A3.96 3.96 0 0 1 18 22a1 1 0 0 1 0-2c.534 0 1.039-.206 1.414-.586c.378-.377.589-.88.586-1.414a1 1 0 0 1 2 0a3.96 3.96 0 0 1-1.172 2.828");
}

</style>
