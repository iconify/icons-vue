<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="xymcs5bbc"/><circle class="rckr-_b7y"/><path class="id9lujbqk"/></g><path class="uph4zqc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-google-16" /></template>
<style>
.id9lujbqk {
  d: path("M28.88 20.611c-.443-.667-1.221-1.111-2.443-1.111h-.223c-1.666 0-3 1.333-3 3v3");
}

.rckr-_b7y {
  cx: 26.214px;
  cy: 25.5px;
  r: 3px;
}

.uph4zqc9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h24l9-9v-24a4 4 0 0 0-4-4m-5 0v37m-19-28v28m28-9h-37m37-19h-28");
}

.xymcs5bbc {
  d: path("m18.786 20.738l2.25-1.238m0 0v9");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
