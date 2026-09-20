<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="wh47r3bor"/><path class="yrdq1-d4b"/><path class="rn46vob-o"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:business-empire" /></template>
<style>
.rn46vob-o {
  d: path("M27.491 38.323c-.165-5.236-.33-10.715.075-15.933c.017-.21.11-.415.247-.592m0 0c.136-.177.314-.328.498-.43l5.995-3.353M14.162 13.52c.141-.225.354-.418.575-.541L20.601 9.7m-6.679 20.388c-.167-5.282-.34-10.817.07-16.087c.013-.168.076-.332.17-.481m3.396-2.118l13.63 8.356m-13.141 7.38c.482.906 1.06 1.588 1.927 2.178l1.156.787c1.06.722 1.926.445 1.926-.615s-.867-2.516-1.926-3.238l-1.253-.852c-1.06-.722-1.926-2.179-1.926-3.238s.867-1.337 1.926-.615l1.156.787c.867.59 1.445 1.176 1.927 2.178m-2.505 6.001v-9.633");
}

.wh47r3bor {
  d: path("m7.519 9.488l26.449 16.045c.912.554 1.647 1.859 1.647 2.926v12.862c0 1.067-.735 1.48-1.647.927L7.519 26.203c-.913-.553-1.647-1.858-1.647-2.926V10.416c0-1.068.734-1.481 1.647-.928");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.yrdq1-d4b {
  d: path("m35.229 42.333l5.252-3.186c.913-.554 1.647-1.859 1.647-2.926V24.686c0-1.067-.734-2.372-1.647-2.925L14.032 5.715c-.499-.302-1.252-.265-1.75.038L6.326 9.365");
}

</style>
