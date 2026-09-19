<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="twm5-kukt"/><path class="p9qh57bfy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:another-widget" /></template>
<style>
.p9qh57bfy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.876 33.687a3.86 3.86 0 0 1-3.404-2.035l-4.33-8.068m13.985 2.746l-1.477-2.746m-6.256.833l1.478-2.747m11.035 2.747l1.477-2.747");
}

.twm5-kukt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.384 33.686a3.86 3.86 0 0 1-3.4-2.033l-2.857-5.323l-2.818 5.252a4 4 0 0 1-.46.7a3.87 3.87 0 0 1-2.956 1.404H8.358a3.86 3.86 0 0 1-3.4-5.683l6.257-11.656a3.859 3.859 0 0 1 6.8 0l2.857 5.323l2.856-5.322a3.859 3.859 0 0 1 6.8 0l2.856 5.323l2.857-5.323a3.858 3.858 0 1 1 6.8 3.65l-6.257 11.655a3.86 3.86 0 0 1-3.4 2.033");
}

</style>
