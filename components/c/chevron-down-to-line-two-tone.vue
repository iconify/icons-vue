<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="s6bq0gb7y"/><path clip-rule="evenodd" class="wn58xnd6a"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevron-down-to-line-two-tone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.s6bq0gb7y {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M17.2929 6.29C17.6834 5.9 18.3164 5.9 18.707 6.29C19.0974 6.68 19.0975 7.32 18.707 7.71L12.707 13.71C12.3165 14.1 11.6834 14.1 11.2929 13.71L5.2929 7.71C4.9024 7.32 4.9024 6.68 5.2929 6.29C5.6834 5.9 6.3164 5.9 6.707 6.29L11.9999 11.59L17.2929 6.29Z");
}

.wn58xnd6a {
  fill-rule: evenodd;
  d: path("M19 16C19.5523 16 20 16.45 20 17C20 17.55 19.5523 18 19 18H5C4.4477 18 4 17.55 4 17C4 16.45 4.4477 16 5 16H19Z");
}

</style>
