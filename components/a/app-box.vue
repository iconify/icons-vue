<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="c y9tr6bcfx"><path class="tln4mzb2f"/><path class="bkdwnniby"/></g><path class="eox5scbsy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:app-box" /></template>
<style>
.bkdwnniby {
  d: path("m40.9 14.273l-16.839 9.774l-16.906-9.774L23.973 4.5z");
}

.eox5scbsy {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M20.083 6.761v20.486H13.56l10.501 10.476l10.175-10.464l-6.153-.012V6.873");
}

.tln4mzb2f {
  d: path("m40.9 14.273l-.055 19.454L24.061 43.5V24.047zm-16.839 9.774V43.5L7.1 33.727l.055-19.454z");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
