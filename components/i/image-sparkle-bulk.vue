<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qebz58hxe"/><path class="kb75jotve"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:image-sparkle-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kb75jotve {
  d: path("M10 11a1 1 0 0 1 0-2c1.452 0 3-1.548 3-3a1 1 0 0 1 2 0c0 .774.422 1.508.957 2.043c.288.292.626.532.997.707c.328.153.683.25 1.046.25a1 1 0 0 1 0 2c-.363 0-.718.097-1.046.25a3.5 3.5 0 0 0-.997.707a3.5 3.5 0 0 0-.707.997c-.153.328-.25.683-.25 1.046a1 1 0 0 1-2 0c0-1.452-1.548-3-3-3m-7.707 5.293l3-3a2.414 2.414 0 0 1 3.414 0l7 7a.999.999 0 1 1-1.414 1.414l-7-7a.414.414 0 0 0-.586 0l-3 3a.999.999 0 1 1-1.414-1.414");
}

.qebz58hxe {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M2 5a3 3 0 0 1 3-3h14a3 3 0 0 1 3 3v14a3 3 0 0 1-3 3H5a3 3 0 0 1-3-3Z");
}

</style>
