<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x-c3kn17e"/><path class="em57w9skn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:hearing-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.em57w9skn {
  d: path("M1.293 2.707a.999.999 0 1 1 1.414-1.414l20 20a.999.999 0 1 1-1.414 1.414Z");
}

.x-c3kn17e {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m9.14 4.897l-1.43-1.43a7 7 0 0 1 7.371-.752A7 7 0 0 1 19 9c0 1.58-.399 3.106-1.416 4.342Zm-3.358.885l9.487 9.487c-.365.24-.736.473-1.087.733a4.3 4.3 0 0 0-.661.586c-.364.411-.521.864-.521 1.412a3.98 3.98 0 0 1-1.172 2.828A3.998 3.998 0 0 1 5 18V9c0-1.12.266-2.223.782-3.218");
}

</style>
