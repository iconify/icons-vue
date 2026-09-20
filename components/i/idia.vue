<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="er3ap-5xy"/><path class="gopnpzz_y"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:idia" /></template>
<style>
.er3ap-5xy {
  fill: var(--svg-color--ff0ea9, #ff0ea9);
  d: path("M4.97 3.562v16.03c0 .529.422.838.843.838c.31 0 .62-.169.771-.529l6.283-15.76A.836.836 0 0 0 12.09 3H5.532a.56.56 0 0 0-.557.562z");
}

.ft5dv1b6b {
  fill: none;
}

.gopnpzz_y {
  fill: var(--svg-color--00daff, #00daff);
  d: path("m9.222 20.245l5.72-14.646a.55.55 0 0 1 .478-.35a.5.5 0 0 1 .36.113c6.418 5.124 2.779 16.07-6.091 15.625a.535.535 0 0 1-.467-.742");
}

</style>
