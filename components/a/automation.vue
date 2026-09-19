<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ujr2zljve"/><circle class="hnjz5absn"/><path class="gkz3yac-t"/><circle class="g9487ubqx"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:automation" /></template>
<style>
.g9487ubqx {
  cx: 32.95px;
  cy: 17.68px;
  r: 3.96px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.gkz3yac-t {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M29.91 7.14a11 11 0 0 0-2.27.93l.24 4.54l-4.54-.23a10.6 10.6 0 0 0-.93 2.26l3.36 3l-3.36 3.05a11 11 0 0 0 .93 2.31l4.54-.23l-.24 4.53a11 11 0 0 0 2.27.94l3-3.37l3 3.37a11 11 0 0 0 2.26-.94L38 22.76l4.53.23a11 11 0 0 0 .94-2.26l-3.37-3.05l3.37-3a10.7 10.7 0 0 0-.94-2.26l-4.53.19l.23-4.54A11 11 0 0 0 36 7.14l-3 3.37Z");
}

.hnjz5absn {
  cx: 15.05px;
  cy: 30.32px;
  r: 3.96px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.ujr2zljve {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M12 19.77a11 11 0 0 0-2.26.94l.26 4.53L5.44 25a11 11 0 0 0-.94 2.26l3.37 3.05l-3.37 3a10.7 10.7 0 0 0 .94 2.26l4.56-.18l-.23 4.54a11 11 0 0 0 2.26.93l3.05-3.37l3 3.37a10.6 10.6 0 0 0 2.26-.93l-.23-4.54l4.54.23a10.6 10.6 0 0 0 .93-2.26l-3.37-3l3.37-3.05a11 11 0 0 0-.92-2.31l-4.54.23l.23-4.53a10.7 10.7 0 0 0-2.26-.94l-3 3.37Z");
}

</style>
