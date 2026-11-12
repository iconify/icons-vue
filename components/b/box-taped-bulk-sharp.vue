<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jt4jr-dnm"/><path class="siy633ble"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-taped-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.jt4jr-dnm {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.443 1.103l9 4.445a1 1 0 0 1 .557.896v11.112a1 1 0 0 1-.557.896l-9 4.445a1 1 0 0 1-.886 0l-9-4.445A1 1 0 0 1 2 17.556V6.444a1 1 0 0 1 .557-.896l9-4.445c.279-.137.607-.137.886 0");
}

.siy633ble {
  d: path("m17.629 6.994l2.928-1.446a1 1 0 1 1 .886 1.793l-3.362 1.66l-.018.009L13 11.51V22a1 1 0 0 1-2 0V11.51L2.557 7.341a1 1 0 0 1 .886-1.793L12 9.774l3.371-1.665l-7.185-3.548a.999.999 0 1 1 .886-1.793Z");
}

</style>
