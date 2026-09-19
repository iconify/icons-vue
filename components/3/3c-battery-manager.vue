<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q54nnjmpx"/><path class="ryzksnbgx"/><path class="n6oa0ragk"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:3c-battery-manager" /></template>
<style>
.n6oa0ragk {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m32.792 21.425l-1.313 3.727l2.626-.621l-1.313 3.727");
}

.q54nnjmpx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.5 28.826v.12c0 5.362-4.346 9.708-9.708 9.708s-9.708-4.347-9.708-9.708v-9.891c0-5.362 4.347-9.708 9.708-9.708s9.708 4.346 9.708 9.708v.12");
}

.ryzksnbgx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.503 36.181c2.023 1.695 4.208 2.472 9.113 2.472h1.143a7.325 7.325 0 1 0 0-14.65M5.5 11.794c2.028-1.69 4.214-2.46 9.12-2.448l1.14.007a7.325 7.325 0 1 1 0 14.65m-5.632 0h5.631m18.491-7.156h1.25c.691 0 1.249.563 1.249 1.262v13.465c0 .7-.558 1.263-1.25 1.263h-5.413c-.692 0-1.25-.563-1.25-1.263V18.11c0-.699.558-1.262 1.25-1.262h1.249v-1.683h2.915z");
}

</style>
