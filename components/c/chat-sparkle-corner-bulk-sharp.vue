<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="c_bxyol0n"/><path class="lsf0n8swe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:chat-sparkle-corner-bulk-sharp" /></template>
<style>
.c_bxyol0n {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 10H10v7a1 1 0 0 1-1 1H7.414l-3.707 3.707A1 1 0 0 1 2 21V3a1 1 0 0 1 1-1h18a1 1 0 0 1 1 1v6a1 1 0 0 1-1 1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.lsf0n8swe {
  d: path("M12 17a1 1 0 0 1 1-1c.363 0 .718-.097 1.046-.25c.371-.175.709-.415.997-.707c.292-.288.532-.626.707-.997c.153-.328.25-.683.25-1.046a1 1 0 0 1 2 0c0 .363.097.718.25 1.046c.175.371.415.709.707.997c.288.292.626.532.997.707c.328.153.683.25 1.046.25a1 1 0 0 1 0 2c-.363 0-.718.097-1.046.25a3.5 3.5 0 0 0-.997.707a3.5 3.5 0 0 0-.707.997c-.153.328-.25.683-.25 1.046a1 1 0 0 1-2 0c0-.363-.097-.718-.25-1.046a3.5 3.5 0 0 0-.707-.997a3.5 3.5 0 0 0-.997-.707A2.5 2.5 0 0 0 13 18a1 1 0 0 1-1-1");
}

</style>
