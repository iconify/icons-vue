<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="l1e5pd3re"/><path clip-rule="evenodd" class="bbw8_4bte"/><path class="bw6jk063v"/><path clip-rule="evenodd" class="rn75x_bxd"/><path clip-rule="evenodd" class="nnamxwb1b"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:countdown-off" /></template>
<style>
.bbw8_4bte {
  fill-rule: evenodd;
  d: path("M6.394 11.447a1 1 0 0 0-.447-1.341l-2-1a1 1 0 1 0-.894 1.789l2 1a1 1 0 0 0 1.341-.448");
}

.bw6jk063v {
  d: path("M8.5 3.5a1 1 0 1 1-2 0a1 1 0 0 1 2 0M6 5a1 1 0 1 1-2 0a1 1 0 0 1 2 0M4.5 7.5a1 1 0 1 1-2 0a1 1 0 0 1 2 0");
}

.cuyn6tgcc {
  fill: currentColor;
}

.l1e5pd3re {
  fill-rule: evenodd;
  d: path("M9.5 3a1 1 0 0 1 1-1a8 8 0 1 1-8 8a1 1 0 0 1 2 0a6 6 0 1 0 6-6a1 1 0 0 1-1-1");
}

.nnamxwb1b {
  fill-rule: evenodd;
  d: path("M14.5 10a1 1 0 0 1-1 1h-3a1 1 0 1 1 0-2h3a1 1 0 0 1 1 1");
}

.rn75x_bxd {
  fill-rule: evenodd;
  d: path("M4.207 9.293a1 1 0 0 1 0 1.414l-1.5 1.5a1 1 0 0 1-1.414-1.414l1.5-1.5a1 1 0 0 1 1.414 0M10.5 6a1 1 0 0 1 1 1v3a1 1 0 1 1-2 0V7a1 1 0 0 1 1-1");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
