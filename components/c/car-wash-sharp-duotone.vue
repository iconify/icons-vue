<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="qmt0c2b-b"/><path class="h8uojb-ss"/><path class="utz6ekdxt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:car-wash-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.h8uojb-ss {
  d: path("M15.641 12L16.489 14H7.511L8.359 12H15.641ZM8 1C8.472 1 8.916 1.223 9.199 1.601L10.4 3.2C10.789 3.719 11 4.351 11 5C11 6.657 9.657 8 8 8C6.343 8 5 6.657 5 5C5 4.351 5.211 3.719 5.6 3.2L6.8 1.6C7.083 1.222 7.528 1 8 1Z");
}

.qmt0c2b-b {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M16.302 10C16.703 10 17.066 10.24 17.223 10.609L18.237 13H20.5V15.346C20.794 15.809 21 16.411 21 17V20C21 21.657 19.657 23 18 23C16.776 23 15.631 22.051 15.164 21H8.825C8.391 22.124 7.276 23 6 23C4.343 23 3 21.657 3 20V17C3 16.327 3.125 15.839 3.5 15.339V13H5.762L6.777 10.609C6.934 10.24 7.297 10 7.698 10H16.302Z");
}

.utz6ekdxt {
  d: path("M16 1C16.472 1 16.916 1.223 17.199 1.601L18.4 3.2C18.789 3.719 19 4.351 19 5C19 6.657 17.657 8 16 8C14.343 8 13 6.657 13 5C13 4.351 13.211 3.719 13.6 3.2L14.8 1.6C15.083 1.222 15.528 1 16 1Z");
}

</style>
