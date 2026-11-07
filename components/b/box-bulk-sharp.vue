<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jt4jr-dnm"/><path class="zhnfpxbxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jt4jr-dnm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.443 1.103l9 4.445a1 1 0 0 1 .557.896v11.112a1 1 0 0 1-.557.896l-9 4.445a1 1 0 0 1-.886 0l-9-4.445A1 1 0 0 1 2 17.556V6.444a1 1 0 0 1 .557-.896l9-4.445c.279-.137.607-.137.886 0");
}

.zhnfpxbxt {
  d: path("m12 9.774l8.557-4.227a1.002 1.002 0 0 1 .886 1.794L13 11.51V22a1 1 0 0 1-2 0V11.51L2.557 7.341a1.002 1.002 0 0 1 .886-1.794Z");
}

</style>
