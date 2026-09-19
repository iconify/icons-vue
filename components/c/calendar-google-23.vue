<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="n8_-o73sp"/><path class="gt9e_ubce"/></g><path class="uph4zqc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-google-23" /></template>
<style>
.gt9e_ubce {
  d: path("M24.692 20.278c.667-.556 1.334-.778 2.778-.778h.89c1.221 0 2.221 1 2.221 2.222h0c0 1.222-1 2.222-2.222 2.222h-2.222");
}

.n8_-o73sp {
  d: path("M17.419 22.5c0-1.667 1.333-3 2.889-3s3 1.333 3 3c0 .778-.334 1.556-.89 2.111c-1.221 1-5 3.889-5 3.889h5.89m5.051-4.556c1.222 0 2.222 1 2.222 2.223h0c0 1.222-1 2.222-2.222 2.222h-.889c-1.555 0-2.111-.222-2.778-.778");
}

.uph4zqc9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h24l9-9v-24a4 4 0 0 0-4-4m-5 0v37m-19-28v28m28-9h-37m37-19h-28");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
