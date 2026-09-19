<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="f-i3y9aqg"/><path class="kp4q75pah"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:linksys" /></template>
<style>
.f-i3y9aqg {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M7.564 6.999V42.5h31.557");
}

.kp4q75pah {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.398 6.999V31.98h19.723M35.742 5.5c2.59 0 4.694 2.104 4.694 4.694s-2.104 4.694-4.694 4.694s-4.694-2.104-4.694-4.694S33.15 5.5 35.742 5.5");
}

</style>
