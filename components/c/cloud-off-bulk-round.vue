<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="a-5wrl0vr"/><path class="popaz21gp"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cloud-off-bulk-round" /></template>
<style>
.a-5wrl0vr {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21.655 18.412L8.247 5.004a6.43 6.43 0 0 1 2.89-1.532a6.1 6.1 0 0 1 2.261-.086a6 6 0 0 1 2.151.755c2.147 1.246 3.217 3.547 3.415 5.951a5.002 5.002 0 0 1 2.691 8.32M17 18l1.917 1.917q-.456.084-.917.083H7a6 6 0 0 1-.74-11.955q.104-.284.227-.558Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.popaz21gp {
  d: path("M1.293 3.707a.999.999 0 1 1 1.414-1.414l19 19a.999.999 0 1 1-1.414 1.414Z");
}

</style>
