<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="pmwej9odu"/><path class="x1iqkjyug"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hago" /></template>
<style>
.pmwej9odu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.797 13.407h9.254v5.682a14.62 14.62 0 0 0 11.898 0v-5.682h9.255V43.5h-9.255V28.859c-3.898 1-8 1-11.898 0V43.5H8.797z");
}

.x1iqkjyug {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.95 13.407V4.5h9.254v8.907m-30.407 0V4.5h9.254v8.907");
}

</style>
