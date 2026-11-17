<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ou5c_6b_n"/><path class="ahssj3byj"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:building-1-bulk" /></template>
<style>
.ahssj3byj {
  d: path("M8 13.961c0-.912.414-1.773 1.126-2.342l3-2.4a3 3 0 0 1 3.748 0l3 2.4A3 3 0 0 1 20 13.961V19h1a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2h5ZM18 19v-5.039a1 1 0 0 0-.376-.78l-3-2.401a.995.995 0 0 0-1.248.001l-3.001 2.401a.99.99 0 0 0-.375.779V19Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.ou5c_6b_n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 21H5a1 1 0 0 1-1-1V6a3 3 0 0 1 3-3h3a3 3 0 0 1 3 3v14a1 1 0 0 1-1 1");
}

</style>
