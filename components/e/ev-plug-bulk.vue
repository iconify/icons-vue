<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ki2no3e_n"/><path class="dnti89bie"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:ev-plug-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.dnti89bie {
  d: path("M8.01 8a1 1 0 0 1 0 2H8a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H12a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H16a1 1 0 0 1 0-2Zm-6 5a1 1 0 0 1 0 2H10a1 1 0 0 1 0-2Zm4 0a1 1 0 0 1 0 2H14a1 1 0 0 1 0-2Z");
}

.ki2no3e_n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.895 4h10.21c.922 0 1.793.424 2.361 1.15A9.484 9.484 0 0 1 12 20.485A9.482 9.482 0 0 1 4.534 5.15A3 3 0 0 1 6.895 4");
}

</style>
