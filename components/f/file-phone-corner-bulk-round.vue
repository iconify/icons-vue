<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="e25vz7cbi"/><path class="tyh0dz7zh"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:file-phone-corner-bulk-round" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.e25vz7cbi {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M19.707 8.293A1 1 0 0 1 19 10h-6a3 3 0 0 0-3 3v8a1 1 0 0 1-1 1a5 5 0 0 1-3.536-1.464A4.98 4.98 0 0 1 4 17V7a5 5 0 0 1 5-5h4c.265 0 .52.105.707.293ZM13 6a2 2 0 0 0 2 2h2l-4-4Z");
}

.tyh0dz7zh {
  d: path("M12 3a1 1 0 0 1 1.698-.716l.009.008v.001l6 6A1 1 0 0 1 19 10h-4a3 3 0 0 1-3-3Zm2 4a.997.997 0 0 0 1 1h1.586L14 5.414Zm-.111 5h.444c.601 0 1.172.206 1.65.565c.477.358.835.845 1.057 1.397c.349.875.522 2.062-.182 2.815l.809.809c.531-.503 1.284-.697 2-.697h.444c.697 0 1.226.479 1.523 1.073c.264.528.366 1.119.366 1.705v.444A1.89 1.89 0 0 1 20.111 22a8 8 0 0 1-3.157-.638a8 8 0 0 1-2.578-1.738a8 8 0 0 1-1.738-2.578A8 8 0 0 1 12 13.889A1.89 1.89 0 0 1 13.889 12");
}

</style>
