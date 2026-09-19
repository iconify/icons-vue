<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><path class="kef91sy0p"/><path class="qm5qh-vyt"/></g><path class="r-_-ahv4y"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:homewhiz" /></template>
<style>
.kef91sy0p {
  d: path("M28.194 33.68c1.719-1.27 2.731-3.246 2.738-5.345c0-3.721-3.104-6.737-6.93-6.737c-3.828 0-6.93 3.016-6.931 6.737a6.66 6.66 0 0 0 2.424 5.114");
}

.qm5qh-vyt {
  d: path("M31.178 37.892c3.307-2.225 5.28-5.846 5.29-9.711c.001-6.583-5.58-11.92-12.467-11.92s-12.47 5.336-12.47 11.92c.013 3.686 1.81 7.16 4.867 9.407");
}

.r-_-ahv4y {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M19.113 42.5H9.624a4 4 0 0 1-4-4V18.596a3 3 0 0 1 1.351-2.506L22.351 5.971a3 3 0 0 1 3.298 0L41.025 16.09a3 3 0 0 1 1.35 2.506V38.5a4 4 0 0 1-4 4H28a4 4 0 0 1-4-4v-9.493");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
