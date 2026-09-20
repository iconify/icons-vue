<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="vm9ik8ban"/><path class="uph4zqc9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:calendar-google-31" /></template>
<style>
.uph4zqc9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h24l9-9v-24a4 4 0 0 0-4-4m-5 0v37m-19-28v28m28-9h-37m37-19h-28");
}

.vm9ik8ban {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m26.701 20.725l2.25-1.225m0 0v9M22.715 24c1.222 0 2.222 1 2.222 2.222s-1 2.222-2.222 2.222h-.889c-1.555 0-2.11-.222-2.778-.777m.001-7.334c.666-.555 1.333-.777 2.777-.777h.89c1.221 0 2.221 1 2.221 2.222S23.937 24 22.715 24h-2.222");
}

</style>
