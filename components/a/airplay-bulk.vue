<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="pqo50z7zu"/><path class="t5acoqblj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:airplay-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pqo50z7zu {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 4h7a2 2 0 0 1 2 2v7a2 2 0 0 1-2 2H5a2 2 0 0 1-2-2V6a2 2 0 0 1 2-2Z");
}

.t5acoqblj {
  d: path("M6 16H5a3 3 0 0 1-3-3V6a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v7a3 3 0 0 1-3 3h-1a1 1 0 0 1 0-2h1a1 1 0 0 0 1-1V6a1 1 0 0 0-1-1H5a.997.997 0 0 0-1 1v7a.997.997 0 0 0 1 1h1a1 1 0 0 1 0 2m9 5H9c-.898 0-1.928-.572-2.089-1.521a1.34 1.34 0 0 1 .382-1.186l3-3a2.414 2.414 0 0 1 3.414 0l3 3c.311.31.456.752.382 1.186C16.928 20.428 15.898 21 15 21m-5.586-2h5.172l-2.293-2.293a.414.414 0 0 0-.586 0Z");
}

</style>
