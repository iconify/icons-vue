<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="abqov3baf"/><path class="xxrsnfb5y"/><path class="v-8z_szqt"/><path class="vf5rxoble"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:grinning-face-with-sweat" /></template>
<style>
.abqov3baf {
  cx: 32.18px;
  cy: 32.23px;
  r: 31.629px;
  fill: var(--svg-color--fbbf67, #fbbf67);
}

.v-8z_szqt {
  fill: var(--svg-color--fff, #fff);
  d: path("M48.67 41.524c0 4.347-7.465 7.876-16.668 7.876c-9.195 0-16.662-3.529-16.662-7.876");
}

.vf5rxoble {
  fill: var(--svg-color--58c5e8, #58c5e8);
  d: path("M51.836 19.264c0 3.446 2.299 6.241 5.136 6.241c2.836 0 5.135-2.794 5.135-6.241c0-3.444-2.299-11.946-5.135-11.946c-2.837 0-5.136 8.501-5.136 11.946");
}

.xxrsnfb5y {
  fill: var(--svg-color--633d19, #633d19);
  d: path("M52.05 39.543c0 10.883-8.829 19.714-19.716 19.714c-10.878 0-19.71-8.831-19.71-19.714m16.975-14.048c-1.354-3.7-4.429-7.241-8.672-7.157c-3.959.075-6.345 4.263-7.636 7.434c-.805 1.979 2.399 2.831 3.197.88c.828-2.036 2.049-4.284 4.288-4.965c2.564-.786 4.911 2.736 5.627 4.69c.727 1.99 3.931 1.131 3.196-.882m5.751-.035c1.354-3.7 4.428-7.241 8.673-7.16c3.959.078 6.343 4.265 7.634 7.435c.807 1.981-2.399 2.833-3.195.882c-.828-2.038-2.051-4.284-4.288-4.967c-2.565-.784-4.913 2.738-5.627 4.692c-.731 1.986-3.933 1.127-3.197-.882");
}

</style>
