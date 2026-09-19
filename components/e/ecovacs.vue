<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="s5d82wg-z"/><path class="no7ra6i2c"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:ecovacs" /></template>
<style>
.no7ra6i2c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M23.691 25.38a1.38 1.38 0 1 1 0-2.76h5.22a1.38 1.38 0 1 1 0 2.76z");
}

.s5d82wg-z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.858 36.643a1.5 1.5 0 0 0-1.061 2.56a21.503 21.503 0 0 0 30.406 0a1.5 1.5 0 0 0-2.121-2.12a18.5 18.5 0 0 1-26.164 0a1.5 1.5 0 0 0-1.06-.44m0-25.286a1.5 1.5 0 0 1-1.061-2.56a21.503 21.503 0 0 1 30.406 0a1.5 1.5 0 0 1-2.121 2.12a18.5 18.5 0 0 0-26.164 0a1.5 1.5 0 0 1-1.06.44M30.506 28.14h-7.699c-2.289 0-4.145-1.854-4.145-4.14s1.856-4.14 4.145-4.14h7.7L32.1 17.1h-9.294c-3.815 0-6.908 3.089-6.908 6.9s3.093 6.9 6.908 6.9h9.295z");
}

</style>
