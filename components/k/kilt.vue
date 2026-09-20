<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="t-qiotblr"><path class="zr8y-fbcn"/><path class="wohe_8bfx"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:kilt" /></template>
<style>
.t-qiotblr {
  fill: var(--svg-color--8c175b, #8c175b);
}

.wohe_8bfx {
  d: path("M15.296 3h3.454l-4.421 7.875h-3.454zm-.298 18h3.752l-4.82-9h-3.617zM5.773 10.875h12.454c.292 0 .523.259.523.562c0 .315-.242.563-.523.563H5.773c-.292 0-.523-.259-.523-.563s.242-.562.523-.562");
}

.zr8y-fbcn {
  d: path("M8.063 3h3.374v10.8l-.843-1.8l.844 4.472V21H8.062z");
}

</style>
