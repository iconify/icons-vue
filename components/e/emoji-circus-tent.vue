<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kunnu1c-j"/><path class="cn82_9b1z"/><path class="eirbm1a2q"/><path class="kpyqlfbgu"/><path class="xnwnr5h2f"/><path class="l4mkqfb8v"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-circus-tent" /></template>
<style>
.cn82_9b1z {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 12.649L12.296 23.243h23.408z");
}

.eirbm1a2q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m24 12.649l-4.153 10.594h8.306zm0 14.378l-2.265 8.325h4.53z");
}

.kpyqlfbgu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 23.243h37v12.109h-37z");
}

.kunnu1c-j {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 12.649L5.5 23.243h37z");
}

.l4mkqfb8v {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.847 23.243h8.306v12.109h-8.306zM24 27.027zv8.325z");
}

.xnwnr5h2f {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.674 23.243h22.653v12.109H12.674z");
}

</style>
