<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<g class="cuyn6tgcc"><path class="cq_pm9bod"/><path class="s4tx9qk6z"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="ph:caret-line-right-duotone" /></template>
<style>
.cq_pm9bod {
  d: path("m144 128l-80 80V48Z");
  opacity: var(--svg-opacity--0-2, 0.2);
}

.cuyn6tgcc {
  fill: currentColor;
}

.s4tx9qk6z {
  d: path("M69.66 42.34A8 8 0 0 0 56 48v160a8 8 0 0 0 13.66 5.66l80-80a8 8 0 0 0 0-11.32ZM72 188.69V67.31L132.69 128ZM192 48v160a8 8 0 0 1-16 0V48a8 8 0 0 1 16 0");
}

</style>
