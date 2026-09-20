<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="j_hyrg2tq"/><path class="vx728fw1n"/></g><path class="gdpz_rbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-fossify-13" /></template>
<style>
.gdpz_rbbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.532 9.567h24.936a4 4 0 0 1 4 4V38.5a4 4 0 0 1-4 4H11.532a4 4 0 0 1-4-4V13.567a4 4 0 0 1 4-4M13.715 5.5v4.068M34.14 5.5v4.068M9.731 19.89h28.36");
}

.j_hyrg2tq {
  d: path("m17.238 27.135l2.8-1.54m0 0v11.2m4.289-.945c.773.648 1.608.945 3.483.945h.437a2.8 2.8 0 1 0 0-5.599");
}

.vx728fw1n {
  d: path("M24.326 26.53c.775-.645 1.61-.94 3.485-.935l.436.003a2.8 2.8 0 1 1 0 5.599m-2.152 0h2.152");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
