<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="hbh0v3xql"/><path class="rto02ubmg"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:applock" /></template>
<style>
.hbh0v3xql {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m10.848 21.566l.115 10.385c.047 4.216 7.248 11.504 13.252 11.549s12.937-8.266 12.937-11.922V21.48c-2.763-1.878-7.23-3.794-12.978-3.871c-5.75-.077-8.375.792-13.326 3.957");
}

.rto02ubmg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.924 19.254s-.02-4.048 0-6.072C14.977 7.825 19.669 4.464 24 4.5c4.62.039 8.896 3.342 9.064 8.642v2.555M23.4 29.464a1.931 1.931 0 0 1 .66-3.746a1.931 1.931 0 0 1 .661 3.746m.001 0l1.195 6.356H22.18l1.219-6.356");
}

</style>
