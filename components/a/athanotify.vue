<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="eydwcoj9i"/><path class="qt2hv9b0w"/><path class="bg37x4bys"/><path class="qcf5xdb8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:athanotify" /></template>
<style>
.bg37x4bys {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.685 10.859c4.553 0 8.238 3.644 8.238 8.136s-3.685 8.135-8.238 8.135c-4.542 0-8.227-3.644-8.227-8.135s3.685-8.136 8.227-8.136");
}

.eydwcoj9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M42.363 22.73c.698 10.136-6.957 18.964-17.099 19.718S6.336 35.598 5.637 25.462C4.94 15.327 12.594 6.5 22.736 5.744q.626-.045 1.253-.05L42.363 5.5z");
}

.qcf5xdb8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M30.685 13.921v5.36l2.879 2.868");
}

.qt2hv9b0w {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M39.229 30.223c-5.838 5.08-14.688 4.465-19.767-1.373c-5.08-5.838-4.465-14.688 1.373-19.767c-8.592 2.962-13.542 11.773-11.057 19.68c2.485 7.908 11.464 11.916 20.056 8.954c3.934-1.356 7.291-4.034 9.395-7.494");
}

</style>
