<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<path class="oh7-i8bkw"/><path class="v6kp_iblc"/><path class="qr3rz4bob"/><path class="s6ydx6nbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-jsp" /></template>
<style>
.oh7-i8bkw {
  fill: var(--svg-color--fdb940, #fdb940);
  d: path("m29.192 2.5l-6.917 7.492a24.85 24.85 0 0 1-5.091 14.754l6.021 1.49C33.243 16.882 29.192 2.5 29.192 2.5");
}

.qr3rz4bob {
  fill: var(--svg-color--f98200, #f98200);
  d: path("m10.256 23.027l6.944 1.719a24.83 24.83 0 0 0 5.086-14.754Z");
}

.s6ydx6nbn {
  fill: var(--svg-color--1b208b, #1b208b);
  d: path("M19.907 26.466c.608 0 1.2.033 1.782.077L2 21.745s3.663 1.2 8.09 7.755a15.94 15.94 0 0 1 9.817-3.034");
}

.v6kp_iblc {
  fill: var(--svg-color--feb322, #feb322);
  d: path("M22.275 9.992a22 22 0 0 0-.288-4.337L6.726 22.194l10.436 2.585c.011-.011.011-.022.022-.033l-6.939-1.719Z");
}

</style>
