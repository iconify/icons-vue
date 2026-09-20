<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="jhnvw-hjm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:face-left" /></template>
<style>
.jhnvw-hjm {
  fill: currentColor;
  d: path("M8.673 11.635q-.348 0-.587-.23q-.24-.23-.24-.578t.24-.578t.587-.23q.329 0 .559.23t.23.578t-.23.578t-.559.23m4.654 0q-.348 0-.578-.23t-.23-.578t.23-.578t.578-.23t.578.23t.23.578t-.23.578t-.578.23M8.329 15.96q-1.518-.927-2.423-2.495T5 10q0-2.927 2.036-4.963T12 3t4.964 2.036T19 10q0 1.896-.906 3.465t-2.423 2.495l-.738-.72q1.401-.78 2.25-2.177q.848-1.397.817-3.111v-.058q-1.517-.448-2.722-1.461t-1.905-2.43q-1.146 1.326-2.727 2.025t-3.334.614q-.27 0-.548-.028q-.28-.03-.548-.087q-.108.371-.162.727T6 10q0 1.708.845 3.084q.846 1.376 2.222 2.157zm3.575 6.444l-3.308-3.308l3.308-3.288l.688.708l-2.075 2.08h4.887v1h-4.887l2.075 2.1z");
}

</style>
