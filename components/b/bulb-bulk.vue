<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="xyhc90b0f"/><path class="pk-3hg67t"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:bulb-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.pk-3hg67t {
  d: path("M9 20h6a1 1 0 0 1 0 2H9a1 1 0 0 1 0-2");
}

.xyhc90b0f {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 15v1a3 3 0 0 1-3 3h-2a3 3 0 0 1-3-3v-1c0-.17-.141-.401-.225-.542q-.195-.325-.786-1.102C6.013 12.076 5 10.686 5 9a7 7 0 1 1 14 0c0 1.686-1.013 3.076-1.989 4.356q-.591.777-.786 1.102c-.084.141-.225.372-.225.542");
}

</style>
