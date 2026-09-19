<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nmuf57z6j"/><path class="dajnqabwu"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:bible" /></template>
<style>
.dajnqabwu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M34.86 21.28c-2.42 3.28-5.75 6.56-9.85 6.56c-2.92 0-5.46-1.83-7.55-3.84c2.09-2 4.63-3.84 7.55-3.84c4.1 0 7.43 3.28 9.85 6.56");
}

.nmuf57z6j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8.4 6.45v35.1a2 2 0 0 0 1.95 2h2.38V4.5h-2.38A2 2 0 0 0 8.4 6.45m4.33-1.95v39h24.92a2 2 0 0 0 2-2V6.45a2 2 0 0 0-2-1.95Z");
}

</style>
