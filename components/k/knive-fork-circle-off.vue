<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="f047wo6nn"/><path class="orcf8n_8j"/><path class="lcjrjqbnk"/><path class="fd-38-bwg"/><path class="rjdzxvb5c"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:knive-fork-circle-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.f047wo6nn {
  fill-rule: evenodd;
  d: path("M14.27 8.506c0 1.942 1.063 3.308 3 3.994V14a1 1 0 1 0 2 0V4.5a1 1 0 0 0-1.442-.897c-2.316 1.141-3.558 2.799-3.558 4.903m2 0c0-.82.319-1.535 1-2.161v3.971c-.695-.411-1-.999-1-1.81");
}

.fd-38-bwg {
  d: path("M9 5.5a1 1 0 0 1 2 0v9a1 1 0 1 1-2 0z");
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.lcjrjqbnk {
  d: path("M13.717 5.45a1 1 0 1 0-1.998.1c.08 1.603-.002 2.682-.2 3.158c-.096.23-.253.315-.712.288a1 1 0 1 0-.115 1.997c1.258.073 2.23-.446 2.675-1.519c.343-.828.444-2.142.35-4.024");
}

.orcf8n_8j {
  d: path("M16.27 20.5v-5a2 2 0 1 1 4 0v5a2 2 0 0 1-4 0M6.283 5.45a1 1 0 1 1 1.998.1c-.08 1.603.002 2.682.2 3.158c.095.23.253.315.712.288a1 1 0 1 1 .114 1.997c-1.258.073-2.229-.446-2.674-1.519c-.343-.828-.444-2.142-.35-4.024");
}

.rjdzxvb5c {
  d: path("M8 20.5v-5a2 2 0 1 1 4 0v5a2 2 0 1 1-4 0M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
