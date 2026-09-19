<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="q1yu30p4d"/><path class="aytbroahr"/><g class="qx9cbmjjo"><path class="o8s_xsbxw"/><circle class="y_ghr7bjv"/></g><path class="z9cxdxbwa"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-flag-rwanda" /></template>
<style>
.aytbroahr {
  fill: var(--svg-color--699635, #699635);
  d: path("M58 47H6c5.2 9 14.9 15 26 15s20.8-6 26-15");
}

.o8s_xsbxw {
  d: path("M58 47c2.6-4.4 4-9.5 4-15H2c0 5.5 1.5 10.6 4 15zM46.2 19.5l8.7-.5l-8.7-.5l8.3-2.8l-8.5 1.8l7.2-4.8l-7.7 3.9l5.7-6.5l-6.5 5.8l3.9-7.8l-4.7 7.3l1.7-8.5l-2.7 8.2l-.5-8.7l-.5 8.7l-2.8-8.2l1.8 8.5l-4.8-7.3l3.9 7.8l-6.5-5.8l5.8 6.5l-7.8-3.9l7.3 4.8l-8.5-1.8l8.2 2.8l-8.6.5l8.6.5l-8.2 2.7l8.5-1.8l-7.3 4.8l7.8-3.9l-5.8 6.5L40 22l-3.9 7.8l4.8-7.3l-1.8 8.5l2.8-8.2l.5 8.7l.5-8.7l2.7 8.2l-1.7-8.5l4.7 7.3l-3.9-7.8l6.5 5.8l-5.7-6.5l7.7 3.9l-7.2-4.8l8.5 1.8z");
}

.q1yu30p4d {
  fill: var(--svg-color--42ade2, #42ade2);
  d: path("M32 2C15.4 2 2 15.4 2 32h60C62 15.4 48.6 2 32 2");
}

.qx9cbmjjo {
  fill: var(--svg-color--ffe62e, #ffe62e);
}

.y_ghr7bjv {
  cx: 42.4px;
  cy: 19px;
  r: 3.7px;
}

.z9cxdxbwa {
  fill: var(--svg-color--42ade2, #42ade2);
  d: path("M42.4 23c-2.2 0-4.1-1.8-4.1-4.1c0-2.2 1.8-4.1 4.1-4.1s4.1 1.8 4.1 4.1s-1.9 4.1-4.1 4.1m0-7.4c-1.8 0-3.3 1.5-3.3 3.3s1.5 3.3 3.3 3.3s3.3-1.5 3.3-3.3s-1.5-3.3-3.3-3.3");
}

</style>
