<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="nwfps6kqr"/><path clip-rule="evenodd" class="ce2so2buk"/><path class="pgxuijb2o"/><path class="x9nhjgblq"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:controller" /></template>
<style>
.ce2so2buk {
  fill-rule: evenodd;
  d: path("M14.5 4h-9a5 5 0 0 0-5 5v2a5 5 0 0 0 5 5h9a5 5 0 0 0 5-5V9a5 5 0 0 0-5-5m-12 5a3 3 0 0 1 3-3h9a3 3 0 0 1 3 3v2a3 3 0 0 1-3 3h-9a3 3 0 0 1-3-3z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.nwfps6kqr {
  d: path("M12.25 10a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5m2 2.5a1.25 1.25 0 1 1 0-2.5a1.25 1.25 0 0 1 0 2.5");
}

.pgxuijb2o {
  d: path("M4 11a1 1 0 1 1 0-2h4a1 1 0 0 1 0 2z");
}

.x9nhjgblq {
  d: path("M7 12a1 1 0 1 1-2 0V8a1 1 0 0 1 2 0z");
}

</style>
