<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="l2tjmdx5r"/><path class="exf4twnco"/><path class="q641bsbtc"/><path class="x4zn9ibvi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:balloon" /></template>
<style>
.exf4twnco {
  fill: var(--svg-color--bb1a34, #bb1a34);
  d: path("M18 25c-1.1 0-1.598-.805-1.105-1.789l1.211-2.422c.492-.984 1.297-.984 1.789 0l1.211 2.422C21.598 24.195 21.1 25 20 25z");
}

.l2tjmdx5r {
  fill: var(--svg-color--fcab40, #fcab40);
  d: path("M27.999 36a1 1 0 0 1-.969-.758c-.036-.136-.926-3.436-4.273-4.272C18.054 29.794 18 23.277 18 23a1 1 0 0 1 .998-.999c.554.034 1 .445 1.002.997c0 .053.054 5.234 3.242 6.032c4.53 1.132 5.682 5.54 5.727 5.728a.998.998 0 0 1-.97 1.242");
}

.q641bsbtc {
  fill: var(--svg-color--bb1a34, #bb1a34);
  d: path("M28 9c0 6-7 12-9 12s-9-6-9-12c0-5.799 4.582-9 9-9s9 3.201 9 9");
}

.x4zn9ibvi {
  fill: var(--svg-color--fcab40, #fcab40);
  d: path("M20 22h-2a1 1 0 1 1 0-2h2a1 1 0 1 1 0 2");
}

</style>
