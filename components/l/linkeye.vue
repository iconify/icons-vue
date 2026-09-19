<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="omohucbxt"/><path class="ao-i57bkn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:linkeye" /></template>
<style>
.ao-i57bkn {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("m12.304 24l2.415-2.415L17.135 24l-2.416 2.415Zm18.561 0l2.415-2.415L35.696 24l-2.416 2.415Z");
}

.omohucbxt {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M14.719 14.719L5.44 24l9.28 9.281L24 24ZM24 24l9.281 9.281L42.561 24l-9.28-9.281Z");
}

</style>
