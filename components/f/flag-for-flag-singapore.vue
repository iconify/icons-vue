<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="exc8p7i9t"/><path class="bs1i9bl6b"/><path class="uh1j7ybky"/><path class="mjojesbzj"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flag-for-flag-singapore" /></template>
<style>
.bs1i9bl6b {
  fill: var(--svg-color--ed2939, #ED2939);
  d: path("M36 18V9a4 4 0 0 0-4-4H4a4 4 0 0 0-4 4v9h36z");
}

.exc8p7i9t {
  fill: var(--svg-color--eee, #EEE);
  d: path("M36 27a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V9a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4v18z");
}

.mjojesbzj {
  d: path("M12 7l.225.691h.726l-.588.427l.225.691L12 8.382l-.588.427l.225-.691l-.588-.427h.726zm-2 7l.225.691h.726l-.588.427l.225.691l-.588-.427l-.588.427l.225-.691l-.588-.427h.726zm4 0l.225.691h.726l-.588.427l.225.691l-.588-.427l-.588.427l.225-.691l-.588-.427h.726zm-5-4l.225.691h.726l-.588.427l.225.691L9 11.382l-.588.427l.225-.691l-.588-.427h.726zm6 0l.225.691h.726l-.588.427l.225.691l-.588-.427l-.588.427l.225-.691l-.588-.427h.726z");
  fill: var(--svg-color--eee, #EEE);
}

.uh1j7ybky {
  fill: var(--svg-color--fff, #FFF);
  d: path("M6 11.5c0-2.585 1.624-4.748 3.81-5.336A5.498 5.498 0 0 0 8.5 6a5.5 5.5 0 1 0 0 11c.452 0 .889-.06 1.31-.164C7.624 16.248 6 14.085 6 11.5z");
}

</style>
