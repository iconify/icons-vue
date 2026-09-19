<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="nhnv30bqg"/><path class="wld4iabvr"/><path class="w4rm5sbbi"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-convenience-store" /></template>
<style>
.nhnv30bqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.028 19.95h26.42v12.517H4.552V19.951h2.201m5.138 12.516v-7.363");
}

.w4rm5sbbi {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.173 18.63c0-.708.639-1.266 1.37-1.125c.479.092.862.508.91.996c.035.362-.08.72-.33.94c-.461.407-1.95 1.504-1.95 1.504h2.286m3.026 0v-3.461l-1.85 2.324h2.283");
}

.wld4iabvr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.754 19.214c0 2.033 2.3 3.682 5.137 3.682s5.137-1.649 5.137-3.682s-2.3-3.681-5.137-3.681s-5.137 1.648-5.137 3.681m1.468 5.89h7.339v7.363H8.222zm10.274 0h7.339v7.363h-7.339zm7.339 0h7.338v7.363h-7.338zm7.338 0h7.339v7.363h-7.339z");
}

</style>
