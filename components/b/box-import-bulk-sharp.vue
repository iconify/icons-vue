<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="tie-6s0mv"/><path class="vnkrd2bug"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:box-import-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.tie-6s0mv {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("m12.443 1.103l9 4.445a1 1 0 0 1 0 1.793L13 11.51V22a1 1 0 0 1-1.443.897l-9-4.445A1 1 0 0 1 2 17.556V6.444a1 1 0 0 1 .557-.896l9-4.445c.279-.137.607-.137.886 0");
}

.vnkrd2bug {
  d: path("m12 9.774l8.557-4.226A1.002 1.002 0 0 1 22 6.444V12a1 1 0 0 1-2 0V8.054l-7 3.456V22a1 1 0 0 1-2 0V11.51L2.557 7.341a1 1 0 0 1 .886-1.793ZM17.414 17H21a1 1 0 0 1 0 2h-3.586l1.293 1.293a.999.999 0 1 1-1.414 1.414l-3-3a1 1 0 0 1 0-1.414l3-3a.999.999 0 1 1 1.414 1.414Z");
}

</style>
