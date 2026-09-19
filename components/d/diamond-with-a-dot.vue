<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="inmh_acpp"/><path class="vw0ihua0o"/><path class="i3cnky-ka"/><path class="aphg9ccob"/><path class="wkpigjb5q"/><path class="epx6hkbss"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:diamond-with-a-dot" /></template>
<style>
.aphg9ccob {
  fill: var(--svg-color--439dd7, #439dd7);
  d: path("M54.741 32.518L31.98 54.923L9.219 32.518L31.981 10.11z");
}

.epx6hkbss {
  fill: var(--svg-color--8dcbef, #8dcbef);
  d: path("M31.981 10.11L21.706 32.518L31.98 54.923L9.219 32.518z");
}

.i3cnky-ka {
  fill: var(--svg-color--0867a3, #0867a3);
  d: path("m24.351 56.16l4.182 4.182a4.876 4.876 0 0 0 6.894 0l25.09-25.09a4.874 4.874 0 0 0 0-6.895l-25.09-25.09c14.376 25.297-4 46.19-11.08 52.887");
}

.inmh_acpp {
  fill: var(--svg-color--25333a, #25333a);
  d: path("M.002 31.803L31.984-.18l31.982 31.982l-31.982 31.982z");
}

.vw0ihua0o {
  fill: var(--svg-color--724198, #724198);
  d: path("M60.51 28.355a4.874 4.874 0 0 1 0 6.895L35.42 60.34a4.876 4.876 0 0 1-6.894 0L3.436 35.25a4.875 4.875 0 0 1 0-6.892l25.09-25.09a4.873 4.873 0 0 1 6.893 0l25.09 25.09");
}

.wkpigjb5q {
  fill: var(--svg-color--fff, #fff);
  d: path("m38.59 32.518l-6.609 6.502l-6.608-6.502l6.608-6.508z");
}

</style>
