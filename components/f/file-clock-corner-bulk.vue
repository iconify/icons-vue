<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ci4d-ib1s"/><path class="intg0xb3w"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-clock-corner-bulk" /></template>
<style>
.ci4d-ib1s {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.707 8.293A1 1 0 0 1 19 10h-8a.997.997 0 0 0-1 1v10a1 1 0 0 1-1 1H7a3 3 0 0 1-3-3V5a3 3 0 0 1 3-3h6c.265 0 .52.105.707.293ZM13 6a2 2 0 0 0 2 2h2l-4-4Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.intg0xb3w {
  d: path("M12 3a1.002 1.002 0 0 1 1.707-.707l6 6A1 1 0 0 1 19 10h-4a3 3 0 0 1-3-3Zm2 4a.997.997 0 0 0 1 1h1.586L14 5.414Zm-2.97 10.603a6.001 6.001 0 1 1 11.941-1.205a6.001 6.001 0 0 1-11.941 1.205m2.284.953a4 4 0 1 0 7.371-3.113a4 4 0 0 0-7.371 3.113M19 16a1 1 0 0 1 0 2h-2a1 1 0 0 1-1-1v-2a1 1 0 0 1 2 0v1Z");
}

</style>
