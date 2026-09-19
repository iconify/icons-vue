<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="qy3b28l1i"/><path class="ysw10ldzo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:emoji-scroll" /></template>
<style>
.qy3b28l1i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m9.2 38.602l-3.7.148v3.73h37v-5.21l-3.7.148m0-28.02l3.7-.148V5.52h-37v5.21l3.7-.148");
}

.ysw10ldzo {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m38.8 9.398l-15.817.633l-13.783.551m0 28.02l29.6-1.184M9.2 10.582v28.02M38.8 9.398v28.02M12.79 15.777h8.147M12.79 19.66h23.064M12.79 23.544h23.064M12.79 27.428h23.064M12.79 31.312h23.064");
}

</style>
