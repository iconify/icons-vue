<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="tueg_3b6f"/><path class="o8rcj4b9e"/><circle transform="rotate(-76.714 15.87 15.994)" class="vsz6jacge"/><path class="p9vmjfbmu"/><path class="ybpqk1lxq"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:dango" /></template>
<style>
.o8rcj4b9e {
  fill: var(--svg-color--fcb1e3, #fcb1e3);
  d: path("M15.254 8.627a6.752 6.752 0 1 1-13.504 0a6.752 6.752 0 0 1 13.504 0");
}

.p9vmjfbmu {
  fill: var(--svg-color--a6d388, #a6d388);
  d: path("M29.987 23.359a6.754 6.754 0 0 1-13.505 0a6.752 6.752 0 0 1 13.505 0");
}

.tueg_3b6f {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M33.875 35.228c-.314 0-.628-.12-.868-.359L2.366 4.227a1.228 1.228 0 0 1 1.736-1.736l30.641 30.641a1.228 1.228 0 0 1-.868 2.096");
}

.vsz6jacge {
  cx: 15.869px;
  cy: 15.994px;
  r: 6.752px;
  fill: var(--svg-color--ffd983, #ffd983);
}

.ybpqk1lxq {
  fill: var(--svg-color--d99e82, #d99e82);
  d: path("M33.875 35.228c-.314 0-.628-.12-.868-.359l-7.52-7.52a1.226 1.226 0 1 1 1.736-1.736l7.52 7.52a1.228 1.228 0 0 1-.868 2.095");
}

</style>
