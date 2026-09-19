<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ted4w31gl"/><path class="gdpz_rbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-fossify-23" /></template>
<style>
.gdpz_rbbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.532 9.567h24.936a4 4 0 0 1 4 4V38.5a4 4 0 0 1-4 4H11.532a4 4 0 0 1-4-4V13.567a4 4 0 0 1 4-4M13.715 5.5v4.068M34.14 5.5v4.068M9.731 19.89h28.36");
}

.ted4w31gl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.314 29.329c0-2.074 1.659-3.734 3.595-3.734s3.733 1.66 3.733 3.734c0 .968-.415 1.935-1.106 2.627c-1.521 1.244-6.222 4.84-6.222 4.84h7.328m2.993-.946c.773.648 1.608.945 3.482.945h.437a2.8 2.8 0 0 0 2.8-2.8v0a2.8 2.8 0 0 0-2.8-2.798m-3.921-4.667c.775-.645 1.61-.94 3.486-.935l.435.003a2.8 2.8 0 0 1 2.8 2.8v0a2.8 2.8 0 0 1-2.8 2.799m-2.152 0h2.152");
}

</style>
