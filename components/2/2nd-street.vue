<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="winv4obyr"/><path class="cz4cnl11u"/><path class="rojzuvgmn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:2nd-street" /></template>
<style>
.cz4cnl11u {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M10.5 7.309a5 5 0 0 0-4.33 7.5l13.5 23.383a5 5 0 0 0 8.66 0l13.5-23.383a5 5 0 0 0-4.33-7.5z");
}

.rojzuvgmn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m21 8.309l3 1.5l-3 1.5m-3.117 15.789l-2.799-1.848l.201 3.348m17.832-6.696l-.201 3.348l2.799-1.848m-15.94-4.512c0-2.555 2.362-4.57 5.064-4.061c1.771.333 3.186 1.835 3.363 3.595c.13 1.309-.292 2.6-1.215 3.394c-1.709 1.47-7.212 5.431-7.212 5.431h8.45");
}

.winv4obyr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 9.809H10.5c-1.925 0-3.128 2.083-2.166 3.75l4.767 8.256m19.815 3.435l6.75-11.691c.962-1.667-.241-3.75-2.166-3.75H28M15.067 25.22l6.767 11.721a2.5 2.5 0 0 0 4.332 0l4.767-8.256");
}

</style>
