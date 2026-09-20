<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="yj1ds8bqp"/><path clip-rule="evenodd" class="szjnd0fqa"/><path class="vybz0-xgg"/><path class="ayqpjc5sn"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:bluetooth" /></template>
<style>
.ayqpjc5sn {
  d: path("M11.526 10.802a1 1 0 1 0-1.195-1.604l-6.965 5.195a1 1 0 0 0 1.196 1.603z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.szjnd0fqa {
  fill-rule: evenodd;
  d: path("m11.535 19.295l5.572-4.25a1 1 0 0 0 0-1.59l-5.572-4.25A1 1 0 0 0 9.93 10v8.5a1 1 0 0 0 1.606.795m.394-7.274l2.922 2.229l-2.922 2.23z");
}

.vybz0-xgg {
  d: path("M11.526 9.198a1 1 0 1 1-1.195 1.604L3.366 5.607a1 1 0 1 1 1.196-1.603z");
}

.yj1ds8bqp {
  fill-rule: evenodd;
  d: path("m11.535 10.795l5.572-4.25a1 1 0 0 0 0-1.59L11.535.705A1 1 0 0 0 9.93 1.5V10a1 1 0 0 0 1.606.795m.394-7.274l2.92 2.229l-2.92 2.23z");
}

</style>
