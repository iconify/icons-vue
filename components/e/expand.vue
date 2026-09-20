<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="bod25nbdw"/><path class="xoen9sl1a"/><path class="cf7y0id-t"/><path class="t_21e8bxb"/><path class="teoo7cxxi"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:expand" /></template>
<style>
.bod25nbdw {
  d: path("M5.707 15.707a1 1 0 0 1-1.414-1.414l4-4a1 1 0 1 1 1.414 1.414z");
}

.cf7y0id-t {
  d: path("M6 15a1 1 0 1 1-2 0v-4a1 1 0 1 1 2 0zm5.707-5.293a1 1 0 0 1-1.414-1.414l4-4a1 1 0 1 1 1.414 1.414z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.t_21e8bxb {
  d: path("M16 9a1 1 0 1 1-2 0V5a1 1 0 1 1 2 0z");
}

.teoo7cxxi {
  d: path("M11 6a1 1 0 1 1 0-2h4a1 1 0 1 1 0 2z");
}

.xoen9sl1a {
  d: path("M5 16a1 1 0 1 1 0-2h4a1 1 0 1 1 0 2z");
}

</style>
