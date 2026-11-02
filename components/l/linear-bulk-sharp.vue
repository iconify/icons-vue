<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="x4l47ab3d"/><path class="wrwlekzhx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:linear-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.wrwlekzhx {
  d: path("m4.014 8.964l11.022 11.022a1 1 0 0 1-1.373 1.453l-.001-.001l-.039-.037L2.6 10.378l-.038-.04h-.001a1 1 0 0 1 1.453-1.374m.591 6.248l4.183 4.183a.999.999 0 1 1-1.414 1.414l-4.183-4.183a1 1 0 0 1-.263-.462v-.002a1 1 0 0 1 1.677-.95");
}

.x4l47ab3d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.293 19.415L4.585 6.707a1 1 0 0 1-.038-1.374a9.998 9.998 0 0 1 17.449 6.945a10 10 0 0 1-3.329 7.175a1 1 0 0 1-1.374-.038");
}

</style>
