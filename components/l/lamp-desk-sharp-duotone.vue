<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="zg1753l7d"/><path class="ih1_mcc0v"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lamp-desk-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.ih1_mcc0v {
  d: path("M9.745 2.262C10.671 1.336 12.171 1.336 13.096 2.262C13.178 2.344 13.329 2.406 13.521 2.379C14.77 2.204 16.624 2.136 18.316 2.615C19.268 2.885 19.834 3.63 19.968 4.463C20.096 5.259 19.834 6.103 19.269 6.739L14.477 12.13C13.823 12.866 12.892 13.217 11.994 13.047C11.068 12.871 10.337 12.17 10.094 11.155C9.817 9.997 9.57 8.608 9.469 7.245L9.435 6.663C9.428 6.494 9.364 6.357 9.275 6.267C8.299 5.291 8.298 3.709 9.275 2.732L9.745 2.262Z");
}

.zg1753l7d {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11.249 7.94L6.497 13.63L7.622 16H11.096C11.505 16 11.873 16.249 12.024 16.629L14.024 21.629C14.148 21.937 14.11 22.286 13.924 22.561C13.738 22.835 13.427 23 13.096 23H5C4.668 23 4.358 22.835 4.172 22.561C3.986 22.286 3.948 21.937 4.071 21.629L5.904 17.046L4.417 13.91C4.25 13.558 4.303 13.14 4.553 12.841L9.714 6.659L11.249 7.94ZM10.878 2.543L9.464 3.957L7.921 2.414L9.335 1L10.878 2.543Z");
}

</style>
