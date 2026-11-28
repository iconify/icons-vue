<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="j7z8x8noh"/><path clip-rule="evenodd" class="nxp2xcc_s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:iv-bag-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j7z8x8noh {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M11 17H9C6.239 17 4 14.7614 4 12V5C4 2.7908 5.791 1 8 1H12H16C18.209 1 20 2.7908 20 5V12C20 14.7614 17.761 17 15 17H13V19C13 19.4401 12.929 19.8655 12.796 20.2641C12.663 20.6624 12.47 21.0323 12.228 21.363C11.985 21.6936 11.694 21.9854 11.363 22.2277C11.032 22.4701 10.662 22.6633 10.264 22.7959C9.865 22.9286 9.44 23 9 23H7C6.448 23 6 22.5523 6 22C6 21.4477 6.448 21 7 21H9C9.223 21 9.435 20.964 9.632 20.8983C9.83 20.8324 10.015 20.7362 10.181 20.6147C10.347 20.4931 10.493 20.3465 10.615 20.1806C10.736 20.0148 10.832 19.8302 10.898 19.6324C10.964 19.4349 11 19.2227 11 19V17Z");
}

.nxp2xcc_s {
  fill-rule: evenodd;
  d: path("M12 10H5C4.448 10 4 10.4477 4 11V12C4 14.7614 6.239 17 9 17H15C17.761 17 20 14.7614 20 12V11C20 10.4477 19.552 10 19 10H12ZM13.5 6.5C13.5 7.3284 12.828 8 12 8C11.172 8 10.5 7.3284 10.5 6.5C10.5 5.6716 11.172 5 12 5C12.828 5 13.5 5.6716 13.5 6.5Z");
}

</style>
