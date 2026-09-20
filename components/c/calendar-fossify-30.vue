<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="s6uz7sxqb"/><path class="lwus-vbkj"/></g><path class="gdpz_rbbn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-fossify-30" /></template>
<style>
.gdpz_rbbn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.532 9.567h24.936a4 4 0 0 1 4 4V38.5a4 4 0 0 1-4 4H11.532a4 4 0 0 1-4-4V13.567a4 4 0 0 1 4-4M13.715 5.5v4.068M34.14 5.5v4.068M9.731 19.89h28.36");
}

.lwus-vbkj {
  d: path("M15.593 26.64c.775-.646 1.61-.94 3.485-.936l.436.003a2.8 2.8 0 1 1 0 5.599m-2.152-.001h2.152");
}

.s6uz7sxqb {
  d: path("M25.079 33.081c0 2.074 1.659 3.733 3.733 3.733s3.595-1.659 3.595-3.733v-3.733c0-2.074-1.66-3.734-3.595-3.734s-3.733 1.66-3.733 3.734zm-9.485 2.879c.773.647 1.608.944 3.483.944h.437a2.8 2.8 0 1 0 0-5.599");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
