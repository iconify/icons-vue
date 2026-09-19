<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="kf3eyknop"/><path class="gdpz_rbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-fossify-3" /></template>
<style>
.gdpz_rbbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.532 9.567h24.936a4 4 0 0 1 4 4V38.5a4 4 0 0 1-4 4H11.532a4 4 0 0 1-4-4V13.567a4 4 0 0 1 4-4M13.715 5.5v4.068M34.14 5.5v4.068M9.731 19.89h28.36");
}

.kf3eyknop {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.641 35.85c.773.648 1.608.945 3.483.945h.437a2.8 2.8 0 0 0 2.799-2.8v0a2.8 2.8 0 0 0-2.8-2.798m-3.92-4.667c.775-.645 1.61-.94 3.485-.935l.436.003a2.8 2.8 0 0 1 2.799 2.8v0a2.8 2.8 0 0 1-2.8 2.799m-2.151 0h2.152");
}

</style>
