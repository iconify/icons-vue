<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="wzy7rivop"/><path class="jo9hslb7k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:fastient" /></template>
<style>
.jo9hslb7k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.9 7.151s5.2 3.8 6 5.9m-9.6-2.3s3.8 5.4 5.9 6m-4.1-7.8l5.699 5.7");
}

.wzy7rivop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M40.097 34.05a16.914 16.914 0 0 0-14.599-25.6a17.7 17.7 0 0 0-5.2.8M9.2 20.55a18.5 18.5 0 0 0-.7 4.8a16.984 16.984 0 0 0 16.97 16.999h.029a17.2 17.2 0 0 0 8.199-2.1M5.5 12.55c2.4 3.6 5 8.1 11.6 6.6c2.2 2.5 15.798 17 18.898 20.4a.91.91 0 0 0 1.1.2c.1 0 .1-.1.2-.2l1.1-1.1l1.1-1.1a.91.91 0 0 0 0-1.2c-3.3-3.1-17.799-16.7-20.399-18.9c1.6-6.699-2.8-9.299-6.6-11.598");
}

</style>
