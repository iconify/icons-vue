<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="rgcsbg3se"/><path clip-rule="evenodd" class="nelfvch4l"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:light-min-two-tone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.nelfvch4l {
  fill-rule: evenodd;
  d: path("M2 15C2.5523 15 3 15.45 3 16C3 16.55 2.5523 17 2 17C1.4477 17 1 16.55 1 16C1 15.45 1.4477 15 2 15ZM22 15C22.5523 15 23 15.45 23 16C23 16.55 22.5523 17 22 17C21.4477 17 21 16.55 21 16C21 15.45 21.4477 15 22 15ZM6.5 9.5C7.0523 9.5 7.5 9.95 7.5 10.5C7.5 11.05 7.0523 11.5 6.5 11.5C5.9477 11.5 5.5 11.05 5.5 10.5C5.5 9.95 5.9477 9.5 6.5 9.5ZM17.5 9.5C18.0523 9.5 18.5 9.95 18.5 10.5C18.5 11.05 18.0523 11.5 17.5 11.5C16.9477 11.5 16.5 11.05 16.5 10.5C16.5 9.95 16.9477 9.5 17.5 9.5ZM12 7C12.5523 7 13 7.45 13 8C13 8.55 12.5523 9 12 9C11.4477 9 11 8.55 11 8C11 7.45 11.4477 7 12 7Z");
}

.rgcsbg3se {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16 15C16.5523 15 17 15.45 17 16C17 16.55 16.5523 17 16 17H8C7.4477 17 7 16.55 7 16C7 15.45 7.4477 15 8 15H16Z");
}

</style>
