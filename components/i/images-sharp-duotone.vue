<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="cuyn6tgcc"><path class="f25-abcaq"/><path class="qd-04tb4z"/><path class="uhhjih-qn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="keyline-icons:images-sharp-duotone" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f25-abcaq {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M4 7V20H17V22H3C2.448 22 2 21.55 2 21V7H4Z");
}

.qd-04tb4z {
  fill-opacity: var(--svg-fill-opacity--0-4, 0.4);
  d: path("M21 2C21.552 2 22 2.45 22 3V17C22 17.55 21.552 18 21 18H7C6.448 18 6 17.55 6 17V3C6 2.45 6.448 2 7 2H21Z");
}

.uhhjih-qn {
  d: path("M11.667 9.19L14.866 12.14L17.977 9.99L20 11.85V16H8V12.57L11.667 9.19ZM11 6C11.552 6 12 6.45 12 7C12 7.55 11.552 8 11 8C10.448 8 10 7.55 10 7C10 6.45 10.448 6 11 6Z");
}

</style>
