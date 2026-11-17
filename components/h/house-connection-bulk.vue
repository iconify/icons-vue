<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="mh6-vgp0v"/><path class="efdgh3ppm"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:house-connection-bulk" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.efdgh3ppm {
  d: path("M13 18v2h7a1 1 0 0 1 0 2H4a1 1 0 0 1 0-2h7v-2H7.778a3 3 0 0 1-3-3V9.352a3 3 0 0 1 1.024-2.258L10.024 3.4a3 3 0 0 1 3.952 0l4.222 3.694a3 3 0 0 1 1.024 2.258V15a3 3 0 0 1-3 3Zm-1-2h4.222a1 1 0 0 0 1-1V9.352c0-.288-.124-.563-.341-.753l-4.222-3.694c-.378-.33-.94-.33-1.318 0L7.119 8.599c-.217.19-.341.465-.341.753V15a1 1 0 0 0 1 1Z");
}

.mh6-vgp0v {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.222 18H7.778a3 3 0 0 1-3-3V9.352a3 3 0 0 1 1.024-2.258L10.024 3.4a3 3 0 0 1 3.952 0l4.222 3.694a3 3 0 0 1 1.024 2.258V15a3 3 0 0 1-3 3");
}

</style>
