<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="eagki-4gp"/><path class="ijmjfebty"/><path class="eaki4zbrt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-black-flag" /></template>
<style>
.eagki-4gp {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M48.2.7c-16.6-5.2-22.4 19.4-39 14.2c3 8.3 6 16.5 9 24.8c16.6 5.2 22.4-19.4 39-14.2c-3-8.3-6-16.5-9-24.8");
}

.eaki4zbrt {
  fill: var(--svg-color--d0d0d0, #d0d0d0);
  d: path("m7.7 15.4l.6-.2zM26 64L8.3 15.2l-.6.2L25.4 64z");
}

.ijmjfebty {
  fill: var(--svg-color--94989b, #94989b);
  d: path("m7.7 15.4l-.9.4L24.4 64h1zM27 64L9.1 14.9l-.8.3L26 64z");
}

</style>
