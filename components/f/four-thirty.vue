<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<circle class="yqfvb1bwf"/><circle class="f934iu1fb"/><path class="l6gfs681a"/><path class="njia5m_7i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:four-thirty" /></template>
<style>
.f934iu1fb {
  cx: 18px;
  cy: 18px;
  r: 14px;
  fill: var(--svg-color--e1e8ed, #e1e8ed);
}

.l6gfs681a {
  fill: var(--svg-color--67757f, #67757f);
  d: path("M18 31a1 1 0 0 1-1-1V18a1 1 0 0 1 2 0v12a1 1 0 0 1-1 1");
}

.njia5m_7i {
  fill: var(--svg-color--67757f, #67757f);
  d: path("M24.999 24a1 1 0 0 1-.58-.187l-7-5a1 1 0 1 1 1.162-1.628l7 5A1 1 0 0 1 24.999 24");
}

.yqfvb1bwf {
  cx: 18px;
  cy: 18px;
  r: 18px;
  fill: var(--svg-color--99aab5, #99aab5);
}

</style>
