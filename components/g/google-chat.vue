<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="r5199lbna"/><path class="xw-kppbje"/><path class="ao8yk4b2n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:google-chat" /></template>
<style>
.ao8yk4b2n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.326 16.947c.523-5.38 5.061-9.582 10.583-9.582h14.182c5.522 0 10.06 4.201 10.583 9.582M16.466 21.99s1.959 3.989 7.534 3.989s7.534-3.808 7.534-3.808");
}

.r5199lbna {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M32.199 11.797c6.241 0 11.301 5.06 11.301 11.3S38.44 34.4 32.199 34.4H24.16l-8.737 5.738a1.33 1.33 0 0 1-2.06-1.111v-4.89C8.294 33.02 4.5 28.501 4.5 23.097c0-6.241 5.06-11.301 11.301-11.301z");
}

.xw-kppbje {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M6.326 16.947c.523-5.38 5.061-9.582 10.583-9.582h14.182c5.522 0 10.06 4.201 10.583 9.582");
}

</style>
