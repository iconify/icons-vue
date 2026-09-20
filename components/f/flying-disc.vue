<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="brrz1_b5q"/><ellipse class="kd3lt1bst"/><path class="ulw2-ybtx"/><ellipse class="f1-a8u8hf"/><path class="swv3h2bkj"/><path class="kt9rltb1k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:flying-disc" /></template>
<style>
.brrz1_b5q {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M35 21.526C35 26.758 27.389 31 18 31S1 26.758 1 21.526S7.625 11 18 11s17 5.294 17 10.526");
}

.f1-a8u8hf {
  cx: 18px;
  cy: 18.002px;
  fill: var(--svg-color--ffac33, #ffac33);
  rx: 12px;
  ry: 6px;
}

.kd3lt1bst {
  cx: 18px;
  cy: 19.502px;
  fill: var(--svg-color--ffac33, #ffac33);
  rx: 16px;
  ry: 8.5px;
}

.kt9rltb1k {
  fill: var(--svg-color--e1e8ed, #e1e8ed);
  d: path("M35 1S24.497-.538 15.958 3C6.77 6.807 4 13 4 13c1.541-1.541 5.463-3.079 10.383-3.705c1.777-3.182 6.97-7.391 12.271-7.351c0 0-7.222 1.493-9.759 7.121A37 37 0 0 1 19 9c1.319 0 2.551.118 3.702.303c.68-2.914 3.791-6.264 7.226-6.829c0 0-3.562 1.707-4.845 7.338C29.418 10.981 32 13 32 13c-4-8 3-12 3-12");
}

.swv3h2bkj {
  fill: var(--svg-color--f4900c, #f4900c);
  d: path("M29 18.002c-1.81 3.118-7 4-11 4s-9.19-.882-11-4c-.75-1.292-1.5 1.083.5 3.083S14 24.402 18 24.402s8.5-1.317 10.5-3.317s1.25-4.374.5-3.083");
}

.ulw2-ybtx {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M18 11.331c-6.449 0-11.5 2.491-11.5 5.672s5.051 5.671 11.5 5.671s11.5-2.491 11.5-5.671s-5.052-5.672-11.5-5.672");
}

</style>
