<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="i1ysa4hrz"/><path class="tq52jsfgs"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:calendar-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i1ysa4hrz {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M8.243 4H18a3 3 0 0 1 3 3v2a1 1 0 0 1-1 1h-5.757Zm-3.805.438L10 10H4a1 1 0 0 1-1-1V7c0-1.047.544-2.018 1.438-2.562");
}

.tq52jsfgs {
  d: path("m21.293 22.707l-1.269-1.269C19.429 21.83 18.706 22 18 22H6a3.004 3.004 0 0 1-3-3V7c0-.707.17-1.429.562-2.024L1.293 2.707a.999.999 0 1 1 1.414-1.414l20 20a.999.999 0 1 1-1.414 1.414M11 6a1 1 0 0 1 0-2h4V3a1 1 0 0 1 2 0v1h1a3 3 0 0 1 3 3v7a1 1 0 0 1-2 0V7a1 1 0 0 0-1-1ZM5 7v12a1 1 0 0 0 1 1h12c.176 0 .353-.018.523-.062L5.062 6.477A2 2 0 0 0 5 7");
}

</style>
