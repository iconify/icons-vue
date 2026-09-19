<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="ci-m2q2tz"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:lux-yellow-icon-pack" /></template>
<style>
.ci-m2q2tz {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24 31.4c3.062 0 5.55 2.488 5.55 5.55S27.062 42.5 24 42.5s-5.55-2.488-5.55-5.55S20.938 31.4 24 31.4m-12.95 0c3.062 0 5.55 2.488 5.55 5.55s-2.488 5.55-5.55 5.55s-5.55-2.488-5.55-5.55s2.488-5.55 5.55-5.55m0-25.9c3.062 0 5.55 2.488 5.55 5.55s-2.488 5.55-5.55 5.55s-5.55-2.488-5.55-5.55S7.988 5.5 11.05 5.5m0 12.95c3.062 0 5.55 2.488 5.55 5.55s-2.488 5.55-5.55 5.55S5.5 27.062 5.5 24s2.488-5.55 5.55-5.55M36.95 5.5c3.062 0 5.55 2.488 5.55 5.55s-2.488 5.55-5.55 5.55s-5.55-2.488-5.55-5.55s2.488-5.55 5.55-5.55M24 5.5c3.062 0 5.55 2.488 5.55 5.55S27.062 16.6 24 16.6s-5.55-2.488-5.55-5.55S20.938 5.5 24 5.5m0 12.95c3.062 0 5.55 2.488 5.55 5.55s-2.488 5.55-5.55 5.55s-5.55-2.488-5.55-5.55s2.488-5.55 5.55-5.55M42.5 24v12.95a5.55 5.55 0 1 1-11.1 0V24a5.55 5.55 0 1 1 11.1 0");
}

</style>
