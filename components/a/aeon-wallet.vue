<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="j3s9ivbxi"/><path class="tsay05n6b"/><path class="lfw5xz95o"/><path class="xhbalbb9r"/><path class="rg0fhg3ej"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:aeon-wallet" /></template>
<style>
.j3s9ivbxi {
  width: 37px;
  height: 37px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.lfw5xz95o {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M21.284 14.516c-.002.396-1.961.716-4.377.716c-2.417 0-4.376-.32-4.376-.717c.002-.395 1.96-.716 4.376-.716s4.377.321 4.377.717");
}

.rg0fhg3ej {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.438 12.186h-2.893v4.669h2.893m7.744-.013v-4.644l4.113 4.644v-4.644");
}

.tsay05n6b {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M8 24.027V12c0-2.216 1.784-4 4-4h24c2.216 0 4 1.784 4 4v5.973M26.015 30.204v4.52h2.415m-6.428-4.52v4.52h2.415m9.616-4.52h3.201m-1.601 4.52v-4.52m-24.858 0l1.208 4.52l1.207-4.52l1.208 4.52l1.208-4.52m14.424 2.26h1.575m.839-2.26h-2.415v4.52h2.415m-12.569-1.497h-2.14m-.53 1.497l1.6-4.52l1.6 4.52M42.5 17.5l-37 7m35.391-4.696l-1.609.304m-1.608.305l-1.61.304m-1.608.304l-1.609.305m-1.608.304l-1.609.304m-1.609.305l-1.608.304m-1.609.305l-1.609.304m-1.608.304l-1.61.304m-1.608.305l-1.609.304m-1.608.305l-1.609.304m-1.609.304l-1.608.305m-1.609.304l-1.609.304");
}

.xhbalbb9r {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M17.438 12.186H13.75l-3.755 4.669m13.943-2.335c0 1.409-1.392 2.55-3.11 2.55s-3.111-1.141-3.111-2.55s1.393-2.55 3.11-2.55c1.718 0 3.11 1.14 3.111 2.55");
}

</style>
