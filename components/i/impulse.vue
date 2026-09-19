<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="dpgdio_qg"/><path class="pk_lenbde"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:impulse" /></template>
<style>
.dpgdio_qg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.732 28.554V14.428a4.22 4.22 0 0 0-4.228-4.227h-.906a4.226 4.226 0 0 0-4.236 4.227v19.143a4.22 4.22 0 0 1-4.228 4.228h-.906A4.22 4.22 0 0 1 24 33.571V14.428a4.22 4.22 0 0 0-4.228-4.227h-.906a4.225 4.225 0 0 0-4.236 4.227v19.143a4.22 4.22 0 0 1-4.228 4.228h-.906a4.22 4.22 0 0 1-4.227-4.228V19.445");
}

.pk_lenbde {
  fill: currentColor;
  d: path("M5.268 9.451c.416 0 .75.334.75.75c0 .415-.334.75-.75.75a.75.75 0 0 1-.75-.75c0-.416.335-.75.75-.75m37.464 27.598a.75.75 0 1 1 0 1.5a.75.75 0 0 1 0-1.5");
}

</style>
