<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="ixgx6uj9r"/><path class="uv-d3t5he"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:couch-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ixgx6uj9r {
  d: path("M240 120v48a8 8 0 0 1-8 8H24a8 8 0 0 1-8-8v-48a8 8 0 0 1 8-8V72a8 8 0 0 1 8-8h192a8 8 0 0 1 8 8v40a8 8 0 0 1 8 8");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.uv-d3t5he {
  d: path("M240 106.17V72a16 16 0 0 0-16-16H32a16 16 0 0 0-16 16v34.17A16 16 0 0 0 8 120v48a16 16 0 0 0 16 16h8v16a8 8 0 0 0 16 0v-16h160v16a8 8 0 0 0 16 0v-16h8a16 16 0 0 0 16-16v-48a16 16 0 0 0-8-13.83M224 104h-8a16 16 0 0 0-16 16v16h-64V72h88ZM120 72v64H56v-16a16 16 0 0 0-16-16h-8V72Zm112 96H24v-48h16v24a8 8 0 0 0 8 8h160a8 8 0 0 0 8-8v-24h16Z");
}

</style>
