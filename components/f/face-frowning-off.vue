<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cgjc_bb1i"/><path class="uf50r_q1t"/><path clip-rule="evenodd" class="butb405nl"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:face-frowning-off" /></template>
<style>
.butb405nl {
  fill-rule: evenodd;
  d: path("M12.221 14.628A1 1 0 0 0 13.8 13.4l-.8.6l.8-.601l-.002-.001l-.002-.003l-.003-.005l-.01-.011l-.08-.095a3 3 0 0 0-.191-.188a3.6 3.6 0 0 0-.698-.478C12.192 12.286 11.28 12 10 12s-2.192.286-2.814.618a3.6 3.6 0 0 0-.698.478a3 3 0 0 0-.272.283l-.009.011l-.003.005l-.002.003H6.2c0 .002 0 .002.8.602l-.8-.6a1 1 0 0 0 1.579 1.227l.038-.036c.05-.044.15-.123.31-.209C8.442 14.214 9.029 14 10 14c.97 0 1.558.214 1.873.382a1.6 1.6 0 0 1 .348.245");
}

.cgjc_bb1i {
  fill-rule: evenodd;
  d: path("M10 17.5a7.5 7.5 0 1 0 0-15a7.5 7.5 0 0 0 0 15m0 2a9.5 9.5 0 1 0 0-19a9.5 9.5 0 0 0 0 19");
}

.cuyn6tgcc {
  fill: currentColor;
}

.uf50r_q1t {
  d: path("M8.5 7.25a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0m5.5 0a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
