<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="x-kz1kb7j"/><path class="kl3ya_bdm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:letter-y" /></template>
<style>
.kl3ya_bdm {
  fill: var(--svg-color--fff, #fff);
  d: path("M26.621 9.001c0-1.24-.93-2.263-2.232-2.263c-.807 0-1.52.341-1.922.93l-4.465 6.48l-4.465-6.48c-.403-.589-1.116-.93-1.922-.93c-1.302 0-2.232 1.023-2.232 2.263c0 .496.155.992.434 1.396L15 17.692v8.417A2.89 2.89 0 0 0 17.891 29h.219A2.89 2.89 0 0 0 21 26.109v-8.414l5.188-7.299c.279-.403.433-.899.433-1.395");
}

.x-kz1kb7j {
  fill: var(--svg-color--3b88c3, #3b88c3);
  d: path("M36 32a4 4 0 0 1-4 4H4a4 4 0 0 1-4-4V4a4 4 0 0 1 4-4h28a4 4 0 0 1 4 4z");
}

</style>
