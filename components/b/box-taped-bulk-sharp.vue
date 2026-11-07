<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="nmd21ubvj"/><path class="za9v_7etr"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-taped-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nmd21ubvj {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M22 6.443v11.113a1 1 0 0 1-.557.896l-9 4.445a1 1 0 0 1-.886 0l-9-4.445A1 1 0 0 1 2 17.556V6.444a1 1 0 0 1 .557-.896l3.814-1.883L16.5 8.667l2.258-1.116L8.629 2.549l2.928-1.446c.279-.137.607-.137.886 0l9 4.445l.002.001a1 1 0 0 1 .555.894");
}

.za9v_7etr {
  d: path("m12 9.774l8.557-4.226a1 1 0 1 1 .886 1.793L13 11.51V22a1 1 0 0 1-2 0V11.51L2.557 7.341a1 1 0 0 1 .886-1.793Z");
}

</style>
