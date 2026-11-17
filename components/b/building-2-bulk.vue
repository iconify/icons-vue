<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ou5c_6b_n"/><path class="c7x0mm0ub"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-2-bulk" /></template>
<style>
.c7x0mm0ub {
  d: path("M18.99 21H3a1 1 0 0 1 0-2h8v-8.4a1 1 0 0 1 .375-.781l.751-.6a3 3 0 0 1 3.748 0l3 2.4A3 3 0 0 1 20 13.961V19h1a1 1 0 0 1 0 2h-2ZM13 19h5v-5.039a1 1 0 0 0-.376-.78l-3-2.401a1.01 1.01 0 0 0-.845-.195l-.429.216l-.35.28Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ou5c_6b_n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 21H5a1 1 0 0 1-1-1V6a3 3 0 0 1 3-3h3a3 3 0 0 1 3 3v14a1 1 0 0 1-1 1");
}

</style>
