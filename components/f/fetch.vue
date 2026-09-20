<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<circle class="iahx_8bhi"/><path class="p08vxxb6j"/><path class="fj0rtwtac"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:fetch" /></template>
<style>
.fj0rtwtac {
  fill: var(--svg-color--3c790a, #3c790a);
  d: path("M87.04 140.8a153.6 153.6 0 0 0 51.2-51.2c-.424-15.317 6.682-28.306 15.872-29.013s16.984 11.136 17.408 26.453c15.317.424 27.16 8.218 26.453 17.408s-13.696 16.296-29.013 15.872a153.6 153.6 0 0 0-51.2 51.2c.274 9.908-2.644 19.308-7.655 24.658s-11.354 5.838-16.64 1.28s-8.71-13.47-8.985-23.378c-15.317-.424-27.16-8.218-26.453-17.408S71.723 140.376 87.04 140.8");
}

.iahx_8bhi {
  cx: 128px;
  cy: 128px;
  r: 115.2px;
  fill: var(--svg-color--fff, #fff);
}

.p08vxxb6j {
  fill: var(--svg-color--3c790a, #3c790a);
  d: path("M128 0C57.308 0 0 57.308 0 128s57.308 128 128 128s128-57.308 128-128S198.692 0 128 0m0 25.6c56.554 0 102.4 45.846 102.4 102.4S184.554 230.4 128 230.4S25.6 184.554 25.6 128S71.446 25.6 128 25.6");
}

</style>
