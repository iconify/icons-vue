<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":164};
const content = `<ellipse class="jn8xd0bjj"/><ellipse class="zijb_ev9b"/><path class="xrl4zg5gr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:chroma" /></template>
<style>
.jn8xd0bjj {
  cx: 170.667px;
  cy: 81.92px;
  fill: var(--svg-color--ffde2d, #ffde2d);
  rx: 85.333px;
  ry: 81.92px;
}

.xrl4zg5gr {
  fill: var(--svg-color--ff6446, #ff6446);
  d: path("M170.667 81.92c0 45.243-38.206 81.92-85.334 81.92V81.92zm-85.334 0C85.333 36.677 123.538 0 170.667 0v81.92z");
}

.zijb_ev9b {
  cx: 85.333px;
  cy: 81.92px;
  fill: var(--svg-color--327eff, #327eff);
  rx: 85.333px;
  ry: 81.92px;
}

</style>
