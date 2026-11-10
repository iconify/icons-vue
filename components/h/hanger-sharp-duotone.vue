<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="vfm-nxblk"/><path class="xwr5odmiu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:hanger-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.vfm-nxblk {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12.009 9.98C12.292 9.98 12.564 10.11 12.753 10.32L21.761 20.34C21.991 20.59 22.05 21.02 21.96 21.35C21.799 21.71 21.41 22 21.016 22H3.001C2.607 22 2.248 21.77 2.087 21.41C1.926 21.05 1.992 20.63 2.255 20.34L11.263 10.32C11.453 10.11 11.725 9.98 12.009 9.98Z");
}

.xwr5odmiu {
  d: path("M11.008 2C13.772 2 16.013 4.24 16.013 7C16.013 8.13 15.489 9.1 14.842 9.87C14.219 10.62 13.412 11.26 12.65 11.77L12.215 12.21L10.801 10.79L11.301 10.29L11.375 10.23L11.379 10.22C11.4 10.21 11.428 10.19 11.454 10.17C12.165 9.69 12.828 9.16 13.305 8.59C13.784 8.02 14.011 7.49 14.011 7C14.011 5.34 12.666 4 11.008 4C9.35 4 8.006 5.34 8.006 7V8H6.004V7C6.004 4.24 8.244 2 11.008 2Z");
}

</style>
