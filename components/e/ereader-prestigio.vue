<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="sz0vzpbpe"/><path class="cx0h94_9i"/><path class="c9ohvchaj"/><path class="t11n1oywg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ereader-prestigio" /></template>
<style>
.c9ohvchaj {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.194 10.788H42.5v27.493H26.61a11 11 0 0 1-2.652.608a9.8 9.8 0 0 1-2.495-.587H5.5V10.694h1.667m28.772 16.065h-7.652m7.652 3.218h-7.652");
}

.cx0h94_9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.701 9.3v26.34h11.656c1.876 0 4.496 1.834 4.496 1.834l-.005-26.707c-1.072-1.053-2.6-1.647-4.103-1.656c-4.015.024-8.03.113-12.044.189");
}

.sz0vzpbpe {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35.886 13.639h-7.641m7.694 3.271h-7.652m7.652 3.217h-7.652m7.652 3.302h-7.652M40.005 9.352V35.64H28.35c-1.876 0-4.497 1.834-4.497 1.834l-.005-26.707c1.077-1.058 2.615-1.653 4.125-1.656z");
}

.t11n1oywg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M18.233 20.19c.542.407.993 1.445.903 2.574c-.09.857-.542 1.58-.903 1.85m-8.124-4.107v3.926h2.618l3.385 2.709v-9.434l-3.385 2.799zm9.704-2.077c.948.723 1.715 2.573 1.625 4.604c-.135 1.535-.903 2.799-1.625 3.34");
}

</style>
