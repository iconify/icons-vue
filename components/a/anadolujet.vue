<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="hggsevb9i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:anadolujet" /></template>
<style>
.hggsevb9i {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9 10.743a21.4 21.4 0 0 1 3.628 3.906c1.574 2.19 2.742 4.738 2.962 7.427c.222 2.724-.542 5.465-1.816 7.883a19.6 19.6 0 0 1-2.492 3.66l.609 3.638L39 31.66l-15.135-1.704q-.15-2.034-.335-4.066c-.205-2.263-.45-4.56-1.314-6.661c-.969-2.351-2.694-4.359-4.784-5.807A15.17 15.17 0 0 0 9 10.743");
}

.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

</style>
