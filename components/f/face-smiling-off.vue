<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="cgjc_bb1i"/><path class="uf50r_q1t"/><path clip-rule="evenodd" class="kvs3tubar"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:face-smiling-off" /></template>
<style>
.cgjc_bb1i {
  fill-rule: evenodd;
  d: path("M10 17.5a7.5 7.5 0 1 0 0-15a7.5 7.5 0 0 0 0 15m0 2a9.5 9.5 0 1 0 0-19a9.5 9.5 0 0 0 0 19");
}

.cuyn6tgcc {
  fill: currentColor;
}

.kvs3tubar {
  fill-rule: evenodd;
  d: path("M14.447 12.106a1 1 0 0 1 .447 1.341L14 13l.894.448v.001l-.002.003l-.003.005l-.006.013a2 2 0 0 1-.077.135q-.073.122-.21.307a4.8 4.8 0 0 1-.846.869C12.96 15.412 11.743 16 10 16s-2.96-.588-3.75-1.22a4.8 4.8 0 0 1-.847-.867a4 4 0 0 1-.286-.443l-.006-.013l-.003-.005l-.001-.003c-.001-.001-.001-.002.893-.449l-.894.447a1 1 0 1 1 1.798-.88q.025.046.1.146c.098.13.26.317.496.506c.46.369 1.243.781 2.5.781s2.04-.412 2.5-.78a2.8 2.8 0 0 0 .497-.508a2 2 0 0 0 .114-.17a1 1 0 0 1 1.336-.437");
}

.uf50r_q1t {
  d: path("M8.5 7.25a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0m5.5 0a1.25 1.25 0 1 1-2.5 0a1.25 1.25 0 0 1 2.5 0");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
