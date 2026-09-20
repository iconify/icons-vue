<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="qovi5mbkq"/><path class="kbm7mbljc"/><path class="d3blp0xkh"/><path class="g_2zs9bjv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:japanese-service-charge-button" /></template>
<style>
.d3blp0xkh {
  fill: var(--svg-color--fafafa, #fafafa);
  d: path("M59.2 106.8c-1.6 0-3-.5-4.1-1.5c-1.8-1.8-2.5-3.4-2-5c.4-1.4 1.9-2.7 4.5-3.7c7.3-3.6 12.5-8.3 15.7-14c3.3-6.1 5-14.9 5-26.3v-4.1H50.7v15.6c0 2.3 0 4 .1 5c.1 2-.3 3.3-1.1 4s-2.3 1.1-4.3 1.1c-2.1 0-3.5-.4-4.3-1.1s-1.2-2-1.1-4s.2-3.6.2-5V52.2H29.9c-3 0-5.1 0-6.3.1c-1.8.1-3.1-.3-3.7-1.1c-.6-.7-.9-2.1-.9-4.1c0-2.1.3-3.5 1-4.2c.7-.8 2-1.2 3.9-1c2.4.1 4.4.2 6 .2h10.2v-12c0-1.2 0-2.1-.1-2.7c-.1-2 .2-3.5 1-4.3s2.3-1.3 4.3-1.3c2.1 0 3.6.4 4.5 1.3s1.2 2.4 1 4.5c-.1.5-.1 1.3-.1 2.4v12h27.6V30c0-1.6 0-2.7-.1-3.4c-.1-2.1.2-3.6 1.1-4.4s2.3-1.2 4.5-1.2s3.6.4 4.4 1.2s1.1 2.3.9 4.4c-.1.7-.1 1.8-.1 3.4v12.1h9.8c2.5 0 4.3 0 5.3-.1c2.1-.2 3.4.1 4.1.8s1 2.2 1 4.3s-.3 3.4-1 4.1c-.6.8-1.9 1.1-3.8 1.1c-1.1-.1-2.9-.1-5.5-.1H89v3.5q0 19.5-5.1 30.3c-3.8 8.1-10.6 14.6-20.3 19.7c-1.5.7-2.9 1.1-4.4 1.1");
}

.g_2zs9bjv {
  fill: var(--svg-color--b4e1ed, #b4e1ed);
  d: path("M39.7 12.9c0-2.3-1.6-3-10.8-2.7c-7.7.3-11.5 1.2-13.8 4s-2.9 8.5-3 15.3c0 4.8 0 9.3 2.5 9.3c3.4 0 3.4-7.9 6.2-12.3c5.4-8.7 18.9-10.6 18.9-13.6");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.kbm7mbljc {
  fill: var(--svg-color--8cafbf, #8cafbf);
  d: path("M109.7 4H11.5C7.4 4 4 7.4 4 11.5v97.9c0 4.1 3.3 7.5 7.5 7.5h98.1c4.1 0 7.5-3.3 7.5-7.5V11.5c.1-4.1-3.1-7.4-7.2-7.5z");
}

.qovi5mbkq {
  fill: var(--svg-color--427687, #427687);
  d: path("M116 4H12c-4.4 0-8 3.6-8 8v104c0 4.4 3.6 8 8 8h104c4.4 0 8-3.6 8-8V12c0-4.4-3.6-8-8-8");
}

</style>
