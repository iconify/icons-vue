<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":20,"height":20};
const content = `<g class="cuyn6tgcc"><path clip-rule="evenodd" class="ap361r45y"/><path clip-rule="evenodd" class="xa-9iyy4m"/><path clip-rule="evenodd" class="eeadxbcdb"/><path clip-rule="evenodd" class="qfjvow6hw"/><path class="xedf9ccsf"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="pepicons-pop:folding-stool-off" /></template>
<style>
.ap361r45y {
  fill-rule: evenodd;
  d: path("M3.5 11A1.5 1.5 0 0 1 5 9.5h10a1.5 1.5 0 0 1 0 3H5A1.5 1.5 0 0 1 3.5 11M6 1a1 1 0 0 1 1 1v5a1 1 0 0 1-2 0V2a1 1 0 0 1 1-1");
}

.cuyn6tgcc {
  fill: currentColor;
}

.eeadxbcdb {
  fill-rule: evenodd;
  d: path("M14 1a1 1 0 0 1 1 1v5a1 1 0 1 1-2 0V2a1 1 0 0 1 1-1m1.825 17.565a1 1 0 0 1-1.39.26l-9.5-6.5a1 1 0 0 1 1.13-1.65l9.5 6.5a1 1 0 0 1 .26 1.39");
}

.qfjvow6hw {
  fill-rule: evenodd;
  d: path("M4.175 18.565a1 1 0 0 0 1.39.26l9.5-6.5a1 1 0 1 0-1.13-1.65l-9.5 6.5a1 1 0 0 0-.26 1.39M14 4H6V2h8zm0 3H6V5h8zM2 8a1 1 0 0 1 1-1h2a1 1 0 0 1 0 2H3a1 1 0 0 1-1-1m12 0a1 1 0 0 1 1-1h2a1 1 0 1 1 0 2h-2a1 1 0 0 1-1-1");
}

.xa-9iyy4m {
  fill-rule: evenodd;
  d: path("M6 6a1 1 0 0 1 1 1v2.5a1 1 0 1 1-2 0V7a1 1 0 0 1 1-1m8 0a1 1 0 0 1 1 1v2.5a1 1 0 1 1-2 0V7a1 1 0 0 1 1-1");
}

.xedf9ccsf {
  d: path("M1.293 2.707a1 1 0 0 1 1.414-1.414l16 16a1 1 0 0 1-1.414 1.414z");
}

</style>
