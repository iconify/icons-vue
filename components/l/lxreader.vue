<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="it1rwtbow"><path class="r2sgi7umu"/><path class="s-tzambdy"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lxreader" /></template>
<style>
.it1rwtbow {
  fill: none;
  stroke: currentColor;
  stroke-miterlimit: 15.118;
}

.r2sgi7umu {
  d: path("m5.51 42.5l7.507-37h7.408l-5.943 30.063H26.64L25.347 42.5z");
}

.s-tzambdy {
  d: path("M42.49 24.044h-5.76l-3.591-5.778l-3.566 5.778h-5.632l6.123-9.458l-5.761-9.042h5.529l3.332 5.726l3.204-5.726h5.684l-5.84 9.43z");
}

</style>
