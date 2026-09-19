<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="g06o4rb3m"/><path class="x-g5q8bui"/><path class="uypw1v62q"/><path class="v5ehxrbja"/><path class="ehngzyb5i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:glip" /></template>
<style>
.ehngzyb5i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M28 24a4 4 0 1 0-8 0m8 0a4 4 0 1 1-8 0");
}

.g06o4rb3m {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M45.5 24c0 11.874-9.626 21.5-21.5 21.5S2.5 35.874 2.5 24m43 0c0-11.874-9.626-21.5-21.5-21.5S2.5 12.126 2.5 24");
}

.uypw1v62q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M35 24c0-6.075-4.925-11-11-11s-11 4.925-11 11m22 0c0 6.075-4.925 11-11 11s-11-4.925-11-11");
}

.v5ehxrbja {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M31.5 24a7.5 7.5 0 1 0-15 0m15 0a7.5 7.5 0 1 1-15 0");
}

.x-g5q8bui {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 24c0-8.008-6.492-14.5-14.5-14.5S9.5 15.992 9.5 24m29 0c0 8.008-6.492 14.5-14.5 14.5S9.5 32.008 9.5 24");
}

</style>
