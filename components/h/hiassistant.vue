<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<rect class="te7wk2b5o"/><rect class="hmzdsbblg"/><rect class="i2ti0-b-z"/><rect class="ftkvm53hm"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hiassistant" /></template>
<style>
.ftkvm53hm {
  width: 20px;
  height: 20px;
  x: 5.5px;
  y: 22.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.hmzdsbblg {
  width: 20px;
  height: 14px;
  x: 22.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.i2ti0-b-z {
  width: 14px;
  height: 20px;
  x: 28.5px;
  y: 22.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

.te7wk2b5o {
  width: 14px;
  height: 14px;
  x: 5.5px;
  y: 5.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  rx: 4px;
  ry: 4px;
}

</style>
