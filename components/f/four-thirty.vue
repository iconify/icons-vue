<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rx2i4z0zh"/><path class="vmfssnb7m"/><path class="eb8jszuvy"/><path class="urtd35kgz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:four-thirty" /></template>
<style>
.eb8jszuvy {
  fill: var(--svg-color--85939c, #85939c);
  d: path("M33.88 52.962c0 1.437-.85 2.603-1.89 2.603c-1.045 0-1.893-1.166-1.893-2.603V31.877c0-1.437.848-2.603 1.893-2.603c1.04 0 1.89 1.166 1.89 2.603z");
}

.rx2i4z0zh {
  fill: var(--svg-color--e0e7ec, #e0e7ec);
  d: path("M61.643 31.997c0 16.37-13.272 29.64-29.644 29.64c-16.373 0-29.646-13.27-29.646-29.64C2.353 15.624 15.625 2.352 32 2.352c16.372 0 29.644 13.271 29.644 29.645");
}

.urtd35kgz {
  fill: var(--svg-color--788288, #788288);
  d: path("M46.265 38.859c1.165.841 1.609 2.212.999 3.057c-.613.843-2.057.845-3.219 0L31.69 32.964c-1.163-.842-1.61-2.216-.996-3.057c.61-.846 2.051-.846 3.214-.006z");
}

.vmfssnb7m {
  fill: var(--svg-color--98a9b4, #98a9b4);
  d: path("M31.998 0C14.353 0 0 14.355 0 31.997c0 17.645 14.356 31.997 31.998 31.997c17.645 0 31.999-14.355 31.999-31.997C63.997 14.352 49.644 0 31.998 0m0 57.768c-14.21 0-25.771-11.56-25.771-25.769c0-14.21 11.561-25.77 25.771-25.77c14.208 0 25.769 11.56 25.769 25.77s-11.56 25.769-25.769 25.769");
}

</style>
