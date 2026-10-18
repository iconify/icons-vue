<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ef5bfcbwx"/><path class="xii-u1kii"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:circle-dot-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ef5bfcbwx {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M23 12C23 17.937 17.937 23 12 23C6.063 23 1 17.937 1 12C1 6.063 6.063 1 12 1C17.937 1 23 6.063 23 12Z");
}

.xii-u1kii {
  d: path("M14 12C14 13.1046 13.1046 14 12 14C10.8954 14 10 13.1046 10 12C10 10.8954 10.8954 10 12 10C13.1046 10 14 10.8954 14 12Z");
}

</style>
