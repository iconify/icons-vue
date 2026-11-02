<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="yo0c7gboq"/><path class="hwyqdfbnl"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:cpu-sparkle-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hwyqdfbnl {
  d: path("M9 5a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0Zm4 0a1 1 0 0 1-2 0V3a1 1 0 0 1 2 0ZM5 7a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm2 5a1 1 0 0 1 1-1c.363 0 .718-.097 1.046-.25c.371-.175.709-.415.997-.707c.292-.288.532-.626.707-.997c.153-.328.25-.683.25-1.046a1 1 0 0 1 2 0c0 .363.097.718.25 1.046c.175.371.415.709.707.997c.288.292.626.532.997.707c.328.153.683.25 1.046.25a1 1 0 0 1 0 2c-.363 0-.718.097-1.046.25a3.5 3.5 0 0 0-.997.707a3.5 3.5 0 0 0-.707.997c-.153.328-.25.683-.25 1.046a1 1 0 0 1-2 0c0-.363-.097-.718-.25-1.046a3.5 3.5 0 0 0-.707-.997a3.5 3.5 0 0 0-.997-.707A2.5 2.5 0 0 0 8 13a1 1 0 0 1-1-1m12-5h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2M5 11a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm14 0h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2M5 15a1 1 0 0 1 0 2H3a1 1 0 0 1 0-2Zm14 0h2a1 1 0 0 1 0 2h-2a1 1 0 0 1 0-2M9 19v2a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0m4 0v2a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0m4 0v2a1 1 0 0 1-2 0v-2a1 1 0 0 1 2 0");
}

.yo0c7gboq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 9a5 5 0 0 1 5-5h6a5 5 0 0 1 5 5v6a5 5 0 0 1-1.464 3.536A5 5 0 0 1 15 20H9a5 5 0 0 1-5-5Z");
}

</style>
