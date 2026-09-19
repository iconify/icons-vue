<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="o9-t8tbuu"/><path class="qgvqne4es"/><path class="ayo5-wnjh"/><path class="b51k7tbuo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:all-nippon-airways" /></template>
<style>
.ayo5-wnjh {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m14.231 7.5l7.273 27.143c1.918 5.14 7.16 7.857 13.379 7.857");
}

.b51k7tbuo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12.187 7.5H23.05L42.5 32.003");
}

.o9-t8tbuu {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 42.5h37V28.115L24.806 6.485c-.583-.724-1.392-.985-2.292-.985H11.651l7.809 29.143l-13.96.992z");
}

.qgvqne4es {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m23.146 21.045l5.79-3.345l-2.901 6.786l5.79-3.344m-8.784-2.783l-1.083-1.29m-2.892-.885L26.3 14.56l-4.345 5.066m9.247 8.456l-1.083-1.29m-2.892-.885l7.234-1.624l-4.345 5.066");
}

</style>
