<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="gp_8x1bzb"><path class="nvpq-t4cu"/><path class="co2ttvboc"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:lamp-desk-sharp-fill" /></template>
<style>
.co2ttvboc {
  d: path("M10.171 3.25L8.628 1.707M10.481 7.3L5.32 13.482L6.989 17");
}

.gp_8x1bzb {
  fill: none;
  stroke: currentColor;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--2px, 2px);
}

.nvpq-t4cu {
  fill: currentColor;
  d: path("M11.096 16C11.505 16 11.872 16.25 12.024 16.629L14.024 21.629C14.147 21.937 14.11 22.286 13.924 22.561C13.738 22.835 13.427 23 13.096 23H5C4.668 23 4.358 22.835 4.172 22.561C3.986 22.286 3.948 21.937 4.071 21.629L6.071 16.629C6.223 16.25 6.591 16 7 16H11.096ZM9.745 2.262C10.67 1.337 12.17 1.337 13.096 2.262C13.178 2.344 13.328 2.406 13.52 2.379C14.769 2.204 16.624 2.137 18.315 2.616C19.268 2.885 19.834 3.63 19.968 4.463C20.096 5.259 19.834 6.104 19.268 6.74L14.477 12.13C13.822 12.866 12.892 13.218 11.993 13.047C11.068 12.871 10.337 12.17 10.094 11.156C9.816 9.998 9.57 8.608 9.469 7.245L9.435 6.663C9.427 6.495 9.364 6.357 9.274 6.268C8.298 5.292 8.298 3.709 9.274 2.733L9.745 2.262Z");
  stroke: none;
}

</style>
