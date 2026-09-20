<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="wsfrx89yo"/><path class="i8nop5bjp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:calendar-slash-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i8nop5bjp {
  d: path("M53.92 34.62A8 8 0 0 0 48 32a16 16 0 0 0-16 16v160a16 16 0 0 0 16 16h160a8 8 0 0 0 5.92-13.38ZM73.55 80H48V51.88ZM48 208V96h40.1l101.82 112ZM224 48v129.23a8 8 0 1 1-16 0V96h-73.12a8 8 0 0 1 0-16H208V48h-24v8a8 8 0 0 1-16 0v-8H91.25a8 8 0 0 1 0-16H168v-8a8 8 0 0 1 16 0v8h24a16 16 0 0 1 16 16");
}

.wsfrx89yo {
  d: path("M216 48v40H40V48a8 8 0 0 1 8-8h160a8 8 0 0 1 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

</style>
