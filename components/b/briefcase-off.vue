<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="aq8690iap"/><path clip-rule="evenodd" class="v_oa6t-ao"/><path clip-rule="evenodd" class="gzppxrbin"/><path class="ubz6qzllx"/><path clip-rule="evenodd" class="cu90v6k_q"/><path class="tebe3hblw"/><path clip-rule="evenodd" class="h8za3w3ye"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:briefcase-off" /></template>
<style>
.aq8690iap {
  fill-rule: evenodd;
  d: path("M3.5 11v4a1 1 0 0 0 1 1h11a1 1 0 0 0 1-1v-4h2v4a3 3 0 0 1-3 3h-11a3 3 0 0 1-3-3v-4z");
}

.cu90v6k_q {
  fill-rule: evenodd;
  d: path("M7 10.75a1 1 0 0 1 1 1v1.75a1 1 0 1 1-2 0v-1.75a1 1 0 0 1 1-1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.gzppxrbin {
  fill-rule: evenodd;
  d: path("M7 4.746V6.5H5V4.746a3 3 0 0 1 .09-.727l.061-.247A3 3 0 0 1 8.061 1.5h3.877a3 3 0 0 1 2.91 2.272l.062.247a3 3 0 0 1 .09.727V6.5h-2V4.746a1 1 0 0 0-.03-.242l-.061-.247a1 1 0 0 0-.97-.757H8.061a1 1 0 0 0-.97.757l-.062.247a1 1 0 0 0-.03.242");
}

.h8za3w3ye {
  fill-rule: evenodd;
  d: path("M13 10.75a1 1 0 0 1 1 1v1.75a1 1 0 1 1-2 0v-1.75a1 1 0 0 1 1-1");
}

.tebe3hblw {
  d: path("M13.866 11.5a1 1 0 0 1-1.732 0l-.866-1.5a1 1 0 0 1 .866-1.5h1.732a1 1 0 0 1 .866 1.5z");
}

.ubz6qzllx {
  d: path("M7.866 11.5a1 1 0 0 1-1.732 0L5.268 10a1 1 0 0 1 .866-1.5h1.732a1 1 0 0 1 .866 1.5z");
}

.v_oa6t-ao {
  fill-rule: evenodd;
  d: path("M1 7a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v3a3 3 0 0 1-3 3H4a3 3 0 0 1-3-3zm16 0H3v3a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1z");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
