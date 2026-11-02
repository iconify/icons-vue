<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="h4r06cy5r"/><path class="lk3mfzb5t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-off-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h4r06cy5r {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.818 7.575L8.575 3.332A6.24 6.24 0 0 1 12 5.247a6.24 6.24 0 0 1 3.552-1.939c2.656-.469 5.187.78 6.089 3.393c.254.738.359 1.52.359 2.299c-.001 2.07-.921 3.989-2.14 5.617ZM4.812 3.812l13.045 13.045a27.4 27.4 0 0 1-3.896 3.1c-.482.321-.969.636-1.475.917a1 1 0 0 1-.972 0a22 22 0 0 1-1.475-.917a29 29 0 0 1-3.203-2.46c-1.233-1.096-2.376-2.315-3.271-3.706C2.645 12.359 2.001 10.72 2 9c0-2.148.834-4.165 2.812-5.188");
}

.lk3mfzb5t {
  d: path("M2.293 2.707a.999.999 0 1 1 1.414-1.414l19 19a.999.999 0 1 1-1.414 1.414Z");
}

</style>
