<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="crpksbcyl"/><path class="g2wj9jbhp"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:finshell-wallet" /></template>
<style>
.crpksbcyl {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M5.5 17.279a5.47 5.47 0 0 1 5.48-5.48h26.04a5.47 5.47 0 0 1 5.48 5.48m-37 6.298a5.47 5.47 0 0 1 5.48-5.48h26.04a5.47 5.47 0 0 1 5.48 5.48m-37 .514h5.561c2.321.035 3.774.994 4.23 2.864s1.975 2.414 4.587 2.414h8.244c2.612 0 4.13-.545 4.586-2.414s1.91-2.83 4.23-2.864H42.5");
}

.g2wj9jbhp {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M9.5 5.5h29c2.216 0 4 1.784 4 4v29c0 2.216-1.784 4-4 4h-29c-2.216 0-4-1.784-4-4v-29c0-2.216 1.784-4 4-4");
}

</style>
