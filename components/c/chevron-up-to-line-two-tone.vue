<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="jy_f4lj4w"/><path clip-rule="evenodd" class="by8itvbuq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevron-up-to-line-two-tone" /></template>
<style>
.by8itvbuq {
  fill-rule: evenodd;
  d: path("M19 6C19.5523 6 20 6.45 20 7C20 7.55 19.5523 8 19 8H5C4.4477 8 4 7.55 4 7C4 6.45 4.4477 6 5 6H19Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.jy_f4lj4w {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.3267 10.26C11.7195 9.94 12.3409 9.93 12.707 10.29L18.707 16.29C19.0974 16.68 19.0974 17.32 18.707 17.71C18.3164 18.1 17.6834 18.1 17.2929 17.71L11.9999 12.42L6.707 17.71C6.3164 18.1 5.6834 18.1 5.2929 17.71C4.9024 17.32 4.9024 16.68 5.2929 16.29L11.3267 10.26Z");
}

</style>
