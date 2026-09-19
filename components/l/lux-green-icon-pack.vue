<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q85s6gv3q"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lux-green-icon-pack" /></template>
<style>
.q85s6gv3q {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M11.05 5.5c3.062 0 5.55 2.488 5.55 5.55s-2.488 5.55-5.55 5.55s-5.55-2.488-5.55-5.55S7.988 5.5 11.05 5.5m0 12.95c3.062 0 5.55 2.488 5.55 5.55s-2.488 5.55-5.55 5.55S5.5 27.062 5.5 24s2.488-5.55 5.55-5.55M24 5.5c3.062 0 5.55 2.488 5.55 5.55S27.062 16.6 24 16.6s-5.55-2.488-5.55-5.55S20.938 5.5 24 5.5m0 12.95c3.062 0 5.55 2.488 5.55 5.55s-2.488 5.55-5.55 5.55s-5.55-2.488-5.55-5.55s2.488-5.55 5.55-5.55M36.95 5.5c3.062 0 5.55 2.488 5.55 5.55s-2.488 5.55-5.55 5.55s-5.55-2.488-5.55-5.55s2.488-5.55 5.55-5.55m0 12.95c3.062 0 5.55 2.488 5.55 5.55s-2.488 5.55-5.55 5.55S31.4 27.062 31.4 24s2.488-5.55 5.55-5.55m0 12.95c3.062 0 5.55 2.488 5.55 5.55s-2.488 5.55-5.55 5.55s-5.55-2.488-5.55-5.55s2.488-5.55 5.55-5.55M24 42.5H11.05a5.55 5.55 0 1 1 0-11.1H24a5.55 5.55 0 1 1 0 11.1");
}

</style>
