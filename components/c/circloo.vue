<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><g class="y9tr6bcfx"><path class="w2orf_b4a"/><path class="aalur1buv"/></g><path class="qk7w1wkoj"/><circle class="x5_crccav"/><circle class="osph8yb6q"/><circle class="jo94gbbjx"/><circle class="cmq4qviya"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:circloo" /></template>
<style>
.aalur1buv {
  d: path("M21.213 26.874c1.981 1.713 2.274 4.24 1.653 6.682c-.62 2.442-2.717 4.531-5.316 5.248c-2.6.717-4.98.266-6.947-1.462m18.891 5.148l5.904-6.856m-6.064-6.127l-2.674-.555l-6.135 13.538M5.5 22.248l14.268 5.767M14.8 15.052l11.006 4.36m2.219-2.687l5.407-2.053m7.963-7.93l-14.871 14.87M6.558 6.797l14.581 14.7M6.569 41.214l14.57-14.57m20.1 14.766L26.408 26.58");
}

.cmq4qviya {
  cx: 7.502px;
  cy: 29.906px;
  r: 0.75px;
  fill: currentColor;
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.jo94gbbjx {
  cx: 10.587px;
  cy: 29.507px;
  r: 0.75px;
  fill: currentColor;
}

.osph8yb6q {
  cx: 13.672px;
  cy: 29.107px;
  r: 0.75px;
  fill: currentColor;
}

.qk7w1wkoj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.093 8.363c7.15.11 16.894-.746 23.96-2.844m5.422 5.142c-3.502 8.19-2.344 18.225 5.025 25.57m-13.774-16.82c-.501 3.645.197 10.192 3.073 12.582");
}

.w2orf_b4a {
  d: path("M23.793 20.44c-1.996 0-3.623 1.623-3.623 3.617s1.627 3.619 3.623 3.619s3.623-1.624 3.623-3.619s-1.627-3.618-3.623-3.618");
}

.x5_crccav {
  cx: 16.757px;
  cy: 28.708px;
  r: 0.75px;
  fill: currentColor;
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
