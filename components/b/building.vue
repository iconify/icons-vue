<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path class="hn01gdbsl"/><path class="l_j35sboa"/><path class="ttkzykqcb"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:building" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.hn01gdbsl {
  d: path("M2 18.5a1 1 0 1 1 0-2h16a1 1 0 1 1 0 2z");
}

.l_j35sboa {
  d: path("M6.5 17a1 1 0 1 1-2 0V4.308C4.5 2.51 5.809 1 7.5 1h5c1.691 0 3 1.51 3 3.308V17a1 1 0 1 1-2 0V4.308c0-.752-.482-1.308-1-1.308h-5c-.518 0-1 .556-1 1.308z");
}

.ttkzykqcb {
  d: path("M8 4h1a.5.5 0 0 1 .5.5v1A.5.5 0 0 1 9 6H8a.5.5 0 0 1-.5-.5v-1A.5.5 0 0 1 8 4m3 0h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1-.5-.5v-1A.5.5 0 0 1 11 4m0 3h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1-.5-.5v-1A.5.5 0 0 1 11 7m0 3h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1-.5-.5v-1a.5.5 0 0 1 .5-.5m0 3h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5h-1a.5.5 0 0 1-.5-.5v-1a.5.5 0 0 1 .5-.5M8 7h1a.5.5 0 0 1 .5.5v1A.5.5 0 0 1 9 9H8a.5.5 0 0 1-.5-.5v-1A.5.5 0 0 1 8 7m0 6h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5H8a.5.5 0 0 1-.5-.5v-1A.5.5 0 0 1 8 13m0-3h1a.5.5 0 0 1 .5.5v1a.5.5 0 0 1-.5.5H8a.5.5 0 0 1-.5-.5v-1A.5.5 0 0 1 8 10");
}

</style>
