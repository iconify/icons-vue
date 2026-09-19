<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="oh3d2-7ji"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:avanza" /></template>
<style>
.oh3d2-7ji {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M4.5 26.19h9.75V41.5H4.5zm9.75-6.56H24v21.88h-9.75zM24 13.06h9.75V41.5H24zm9.75-6.56h9.75v35h-9.75z");
}

</style>
