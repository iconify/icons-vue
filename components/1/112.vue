<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="i9clfwm2k"/><path class="pse7tbc2a"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:112" /></template>
<style>
.i9clfwm2k {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M38.5 5.5h-29a4 4 0 0 0-4 4v29a4 4 0 0 0 4 4h29a4 4 0 0 0 4-4v-29a4 4 0 0 0-4-4");
}

.pse7tbc2a {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12 19.231l3.277-1.784v13.106m4.382-11.322l3.276-1.784v13.106m4.382-8.765a4.346 4.346 0 0 1 5.203-4.258c1.82.35 3.275 1.925 3.456 3.77c.135 1.372-.3 2.726-1.248 3.558c-1.756 1.541-7.41 5.695-7.41 5.695H36");
}

</style>
