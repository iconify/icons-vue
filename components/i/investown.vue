<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="x9qq5tb_v"/><path class="r8bdnu2rh"/><path class="b7s7gxbaz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:investown" /></template>
<style>
.b7s7gxbaz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 31.2v-7.83c.457-7.543 11.55-7.912 12.335 0v7.844C17.459 38.037 6.6 38.679 5.5 31.199");
}

.r8bdnu2rh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.834 24.94v-7.83c.457-7.543 11.55-7.912 12.335 0v14.263c-.376 6.822-11.235 7.465-12.335-.015z");
}

.x9qq5tb_v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.165 24.894v-7.828c.457-7.544 11.55-7.913 12.335 0v7.843c-.376 6.823-11.235 7.465-12.335-.015");
}

</style>
