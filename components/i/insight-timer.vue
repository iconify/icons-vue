<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="o5qmh0yvz"/><path class="qzsatzmya"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:insight-timer" /></template>
<style>
.o5qmh0yvz {
  d: path("M4.675 14.582c1.232-.899 10.588-1.549 21.091-1.467c10.504.083 18.33.868 17.644 1.77c-.686.903-9.633 1.594-20.173 1.56c-10.54-.036-18.831-.785-18.694-1.69zm38.498 3.952c-1.875.796-10.192 1.36-19.701 1.338s-17.448-.625-18.807-1.429");
}

.qzsatzmya {
  d: path("M4.564 14.768s-1.02 11.208 5.095 16.118c0 0 3.866 3.978 14.308 3.983c10.517.37 14.374-3.983 14.374-3.983c6.114-4.91 5.095-16.118 5.095-16.118");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
