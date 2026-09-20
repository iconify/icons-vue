<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="lnjkq8-_s"/><path clip-rule="evenodd" class="jsgbi0b9o"/><path clip-rule="evenodd" class="j_gqwwbao"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:arrow-down-left-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.j_gqwwbao {
  fill-rule: evenodd;
  d: path("M7.172 12.829a1 1 0 0 1 0-1.415l5.656-5.656a1 1 0 1 1 1.415 1.414l-5.657 5.657a1 1 0 0 1-1.414 0");
}

.jsgbi0b9o {
  fill-rule: evenodd;
  d: path("M5.903 7.354a1 1 0 0 1 1.086.906l.471 5.185a1 1 0 1 1-1.991.181l-.472-5.185a1 1 0 0 1 .906-1.087");
}

.lnjkq8-_s {
  fill-rule: evenodd;
  d: path("M12.646 14.098a1 1 0 0 1-1.087.905l-5.185-.472a1 1 0 1 1 .181-1.991l5.186.471a1 1 0 0 1 .905 1.087");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
