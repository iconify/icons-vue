<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="ki42p3wpf"/><path class="towqvtbov"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="coolicons:luggage-bulk-sharp" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ki42p3wpf {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7a1 1 0 0 1 1-1h14a1 1 0 0 1 1 1v12a1 1 0 0 1-1 1h-1.171a3 3 0 0 1-5.658 0h-.342a3 3 0 0 1-5.658 0H5a1 1 0 0 1-1-1Zm5.705 12.709l.002-.002l.002-.002a1 1 0 0 0-.002-1.412l-.002-.002a1 1 0 1 0 0 1.418m4.588-.002l.002.002a1 1 0 1 0 0-1.418l-.002.002l-.002.002a1 1 0 0 0 .002 1.412");
}

.towqvtbov {
  d: path("M8 3a1 1 0 0 1 1-1h6a1 1 0 0 1 1 1v4a1 1 0 0 1-2 0V4h-4v3a1 1 0 0 1-2 0ZM6 19a3 3 0 1 1 6 0a3 3 0 0 1-6 0m6.236 1.168a3 3 0 1 1 5.527-2.335a3 3 0 0 1-5.527 2.335M8 19a1 1 0 1 0 2 0a1 1 0 0 0-2 0m6 0a1 1 0 1 0 2 0a1 1 0 0 0-2 0");
}

</style>
