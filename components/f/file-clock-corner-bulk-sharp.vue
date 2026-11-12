<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="bjexm-byy"/><path class="rrlivoeqb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-clock-corner-bulk-sharp" /></template>
<style>
.bjexm-byy {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M13 2c.265 0 .52.105.707.293l6 6A1 1 0 0 1 19 10h-9v11a1 1 0 0 1-1 1H5a1 1 0 0 1-1-1V3a1 1 0 0 1 1-1Zm0 6h4l-4-4Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.rrlivoeqb {
  d: path("M12 3a1.002 1.002 0 0 1 1.707-.707l6 6A1 1 0 0 1 19 10h-6a1 1 0 0 1-1-1Zm2 5h2.586L14 5.414Zm-2.97 9.603a6.001 6.001 0 1 1 11.941-1.205a6.001 6.001 0 0 1-11.941 1.205m2.284.953a4 4 0 1 0 7.371-3.113a4 4 0 0 0-7.371 3.113M19 16a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0v1Z");
}

</style>
