<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="wkm7jw_on"/><path class="i2qu4881j"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:arrow-up-to-line-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.i2qu4881j {
  d: path("M12.005 4.738C12.204 4.776 12.569 4.909 12.713 5.055L20.007 12.476L18.581 13.877L13.206 8.407L13 8.198V23.001H11V8.198L10.794 8.407L5.419 13.877L3.992 12.476L11.334 5.007C11.464 4.903 11.842 4.768 12.005 4.738Z");
}

.wkm7jw_on {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M12 4.754C12.268 4.754 12.525 4.863 12.713 5.054L20.007 12.475L18.581 13.876L13.206 8.406L13 8.197V23H11V8.197L10.794 8.406L5.419 13.876L3.992 12.475L11.338 5.001C11.516 4.856 11.768 4.754 12 4.754ZM20 1V3H4V1H20Z");
}

</style>
