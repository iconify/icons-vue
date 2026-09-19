<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="j33nlef-c"/><path class="ji7z06bzc"/><path class="p4fbbijzc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:huawei-hidisk" /></template>
<style>
.j33nlef-c {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.68 36.934a89 89 0 0 1 18.645.375A9.23 9.23 0 0 0 43.49 28.23a9.924 9.924 0 0 0-10.054-9.904a8.6 8.6 0 0 0-8.178 6.228c-1.527 6.326-6.141 9.256-10.58 12.38Z");
}

.ji7z06bzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.57 18.326c-.975-4.062-4.725-7.69-11.424-7.69c-4.26 0-7.715 2.27-9.378 8.928c-.644 2.574-.18 5.02 1.725 8.854c1.62 3.26 1.546 6.118.188 8.515");
}

.p4fbbijzc {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.477 22.489C9.174 21.678 4.55 24.72 4.5 29.77c-.056 5.698 5.647 7.53 10.18 7.164");
}

</style>
