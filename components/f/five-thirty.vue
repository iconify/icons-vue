<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="l4l79nkwg"/><path class="s-z68fb5t"/><path class="p87lr-bph"/><path class="xxxafsb0f"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:five-thirty" /></template>
<style>
.l4l79nkwg {
  cx: 31.671px;
  cy: 31.671px;
  r: 29.34px;
  fill: var(--svg-color--e0e7ec, #e0e7ec);
}

.p87lr-bph {
  fill: var(--svg-color--85939c, #85939c);
  d: path("M33.531 52.42c0 1.425-.84 2.578-1.871 2.578s-1.872-1.153-1.872-2.578V31.553c0-1.427.839-2.579 1.872-2.579c1.031 0 1.871 1.152 1.871 2.579z");
}

.s-z68fb5t {
  fill: var(--svg-color--98a9b4, #98a9b4);
  d: path("M31.673 0C14.209 0 0 14.208 0 31.673s14.209 31.671 31.673 31.671s31.671-14.207 31.671-31.671C63.346 14.208 49.139 0 31.673 0m0 57.18c-14.07 0-25.507-11.442-25.507-25.508c0-14.07 11.442-25.508 25.507-25.508c14.06 0 25.505 11.442 25.505 25.507c0 14.06-11.442 25.509-25.505 25.509");
}

.xxxafsb0f {
  fill: var(--svg-color--788288, #788288);
  d: path("M41.744 43.35c.734 1.215.611 2.637-.271 3.168c-.887.535-2.199-.022-2.935-1.242l-7.798-12.93c-.732-1.22-.608-2.643.276-3.172c.882-.533 2.199.022 2.931 1.237z");
}

</style>
