<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="acztu2bnh"/><path clip-rule="evenodd" class="p8bn8gbos"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:chevron-right-to-line-two-tone" /></template>
<style>
.acztu2bnh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M6.2929 5.29C6.6834 4.9 7.3164 4.9 7.707 5.29L13.707 11.29C14.0974 11.68 14.0975 12.32 13.707 12.71L7.707 18.71C7.3165 19.1 6.6834 19.1 6.2929 18.71C5.9024 18.32 5.9024 17.68 6.2929 17.29L11.5859 12L6.2929 6.71C5.9024 6.32 5.9024 5.68 6.2929 5.29Z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.p8bn8gbos {
  fill-rule: evenodd;
  d: path("M17 4C17.5523 4 18 4.45 18 5V19C18 19.55 17.5523 20 17 20C16.4477 20 16 19.55 16 19V5C16 4.45 16.4477 4 17 4Z");
}

</style>
