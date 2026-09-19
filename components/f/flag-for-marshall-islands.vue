<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="rzt_y0bvc"/><path class="a56ugdcbt"/><path class="wwqkahays"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-marshall-islands" /></template>
<style>
.a56ugdcbt {
  fill: var(--svg-color--ff8736, #ff8736);
  d: path("M58 17.1c-2.7-4.7-6.7-8.7-11.6-11.4l-43.6 33c.6 3 1.8 5.8 3.2 8.3z");
}

.rzt_y0bvc {
  fill: var(--svg-color--2a5f9e, #2a5f9e);
  d: path("M39.8 3C23.8-1.3 7.3 8.2 3 24.2c-1.3 4.9-1.3 9.9-.3 14.5l43.6-33c-1.9-1.1-4.2-2-6.5-2.7M11.6 54c3.5 3.2 7.7 5.7 12.6 7c16 4.3 32.5-5.2 36.7-21.2c.6-2.3.9-4.6 1-6.9z");
}

.wwqkahays {
  fill: var(--svg-color--fff, #fff);
  d: path("M58 17.1L6 47c1.5 2.6 3.4 4.9 5.6 7L62 32.9c.2-5.6-1.3-11.1-4-15.8m-38.4 1l6.7-.4l-6.7-.4l3.7-1.4l-3.9.7l3.2-2.3l-3.6 1.6l2.5-3.1l-3 2.5l1.6-3.6l-2.3 3.2l.6-3.9l-1.4 3.7l-.4-6.7l-.4 6.7l-1.4-3.7l.6 3.9l-2.3-3.2l1.6 3.6l-3-2.5l2.5 3.1l-3.6-1.6l3.2 2.3l-3.9-.7l3.6 1.4l-6.6.4l6.6.4l-3.6 1.4l3.9-.6l-3.2 2.3l3.6-1.6l-2.5 3.1l3-2.5l-1.6 3.6l2.3-3.2l-.6 3.9l1.4-3.7l.4 6.7l.4-6.7l1.4 3.7l-.6-3.9l2.3 3.2l-1.6-3.6l3 2.5l-2.5-3.1l3.6 1.6l-3.2-2.3l3.9.6z");
}

</style>
