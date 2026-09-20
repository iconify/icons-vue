<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ki2vueivy"/><path class="k62_7hb2l"/><path class="aumi3093e"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:loop-plus" /></template>
<style>
.aumi3093e {
  d: path("M8.207 7.164a1 1 0 0 1 2 0v4a1 1 0 1 1-2 0z");
}

.cuyn6tgcc {
  fill: currentColor;
}

.k62_7hb2l {
  d: path("M11.9 14.728a1.5 1.5 0 1 1 2.12-2.121l3.536 3.535a1.5 1.5 0 1 1-2.121 2.121zm-4.693-4.564a1 1 0 0 1 0-2h4a1 1 0 1 1 0 2z");
}

.ki2vueivy {
  fill-rule: evenodd;
  d: path("M4.828 4.828a6 6 0 1 0 8.486 8.486a6 6 0 0 0-8.486-8.486M11.9 11.9a4 4 0 1 1-5.656-5.656A4 4 0 0 1 11.9 11.9");
}

</style>
