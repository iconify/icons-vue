<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ox1bc9gwd"/><path class="wqtegnfoc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:heart-handshake-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ox1bc9gwd {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 5.247a6.24 6.24 0 0 1 3.552-1.939c2.656-.469 5.187.78 6.089 3.393c.254.738.359 1.52.359 2.299c-.001 1.72-.645 3.359-1.565 4.791c-.895 1.391-2.038 2.61-3.271 3.706a29 29 0 0 1-3.203 2.46c-.482.321-.969.636-1.475.917a1 1 0 0 1-.972 0a22 22 0 0 1-1.475-.917a29 29 0 0 1-3.203-2.46c-1.233-1.096-2.376-2.315-3.271-3.706C2.645 12.359 2.001 10.72 2 9c0-.779.105-1.561.359-2.299c.902-2.613 3.433-3.862 6.089-3.393A6.24 6.24 0 0 1 12 5.247");
}

.wqtegnfoc {
  d: path("M9.707 10.707a1.121 1.121 0 1 0 1.586 1.586l1-1a3.83 3.83 0 0 1 5.414 0l2 2a.999.999 0 1 1-1.414 1.414l-2-2a1.83 1.83 0 0 0-2.586 0l-1 1a3.121 3.121 0 1 1-4.414-4.414l3-3a.999.999 0 1 1 1.414 1.414Zm7.099 5.685a.999.999 0 1 1-1.414 1.414l-2.099-2.099a.999.999 0 1 1 1.414-1.414Zm-2.862 2.138a1 1 0 0 1-1.414 1.414l-2.237-2.237a.999.999 0 1 1 1.414-1.414Z");
}

</style>
