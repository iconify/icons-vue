<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="xcx-turau"/><path class="si68dpdbv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:apparka" /></template>
<style>
.si68dpdbv {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m20.57 7.898l-.226.128a7.053 7.053 0 0 0-2.638 9.642L29.03 37.456a7.104 7.104 0 0 0 9.67 2.646l.226-.128a7.053 7.053 0 0 0 2.638-9.641L30.24 10.542a7.104 7.104 0 0 0-9.67-2.645");
}

.xcx-turau {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m27.43 7.898l.226.128a7.053 7.053 0 0 1 2.638 9.642L18.97 37.456a7.104 7.104 0 0 1-9.67 2.646l-.226-.128a7.053 7.053 0 0 1-2.638-9.641l11.325-19.79a7.104 7.104 0 0 1 9.67-2.645");
}

</style>
