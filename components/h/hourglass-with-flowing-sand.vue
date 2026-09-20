<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="i9heqj3vf"/><path class="uj4w6izxp"/><path class="d1ek3wbqv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:hourglass-with-flowing-sand" /></template>
<style>
.d1ek3wbqv {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M30 34a2 2 0 0 1-2 2H8a2 2 0 0 1 0-4h20a2 2 0 0 1 2 2m0-32a2 2 0 0 1-2 2H8a2 2 0 0 1 0-4h20a2 2 0 0 1 2 2");
}

.i9heqj3vf {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M21 18c0-2.001 3.246-3.369 5-6c2-3 2-10 2-10H8s0 7 2 10c1.754 2.631 5 3.999 5 6s-3.246 3.369-5 6c-2 3-2 10-2 10h20s0-7-2-10c-1.754-2.631-5-3.999-5-6");
}

.uj4w6izxp {
  fill: var(--svg-color--ffac33, #ffac33);
  d: path("M18 2h-8s0 4 1 7c1.304 3.912 6 4.999 6 9s0 13 1 13s1-9 1-13s4.697-5.088 6-9c1-3 1-7 1-7z");
}

</style>
