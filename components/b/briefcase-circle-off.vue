<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":26,"height":26};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="yepojsk3q"/><path clip-rule="evenodd" class="opc_qfy5b"/><path clip-rule="evenodd" class="z4hqnc5ik"/><path class="nxy2nv8vm"/><path clip-rule="evenodd" class="r3_fkgbsi"/><path class="vl2w4lb8e"/><path clip-rule="evenodd" class="yonvdacbv"/><path class="t_j776bmu"/><path clip-rule="evenodd" class="kphejjb8s"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:briefcase-circle-off" /></template>
<style>
.cuyn6tgcc {
  fill: currentColor;
}

.kphejjb8s {
  fill-rule: evenodd;
  d: path("M13 24c6.075 0 11-4.925 11-11S19.075 2 13 2S2 6.925 2 13s4.925 11 11 11m0 2c7.18 0 13-5.82 13-13S20.18 0 13 0S0 5.82 0 13s5.82 13 13 13");
}

.nxy2nv8vm {
  d: path("M10.866 14.5a1 1 0 0 1-1.732 0L8.268 13a1 1 0 0 1 .866-1.5h1.732a1 1 0 0 1 .866 1.5z");
}

.opc_qfy5b {
  fill-rule: evenodd;
  d: path("M4 10a2 2 0 0 1 2-2h14a2 2 0 0 1 2 2v3a3 3 0 0 1-3 3H7a3 3 0 0 1-3-3zm16 0H6v3a1 1 0 0 0 1 1h12a1 1 0 0 0 1-1z");
}

.r3_fkgbsi {
  fill-rule: evenodd;
  d: path("M10 13.75a1 1 0 0 1 1 1v1.75a1 1 0 1 1-2 0v-1.75a1 1 0 0 1 1-1");
}

.t_j776bmu {
  d: path("M4.293 5.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

.vl2w4lb8e {
  d: path("M16.866 14.5a1 1 0 0 1-1.732 0l-.866-1.5a1 1 0 0 1 .866-1.5h1.732a1 1 0 0 1 .866 1.5z");
}

.yepojsk3q {
  fill-rule: evenodd;
  d: path("M6.5 14v4a1 1 0 0 0 1 1h11a1 1 0 0 0 1-1v-4h2v4a3 3 0 0 1-3 3h-11a3 3 0 0 1-3-3v-4z");
}

.yonvdacbv {
  fill-rule: evenodd;
  d: path("M16 13.75a1 1 0 0 1 1 1v1.75a1 1 0 1 1-2 0v-1.75a1 1 0 0 1 1-1");
}

.z4hqnc5ik {
  fill-rule: evenodd;
  d: path("M10 7.746V9.5H8V7.746a3 3 0 0 1 .09-.727l.061-.247a3 3 0 0 1 2.91-2.272h3.877a3 3 0 0 1 2.91 2.272l.062.247a3 3 0 0 1 .09.727V9.5h-2V7.746a1 1 0 0 0-.03-.242l-.061-.247a1 1 0 0 0-.97-.757h-3.877a1 1 0 0 0-.97.757l-.062.247a1 1 0 0 0-.03.242");
}

</style>
