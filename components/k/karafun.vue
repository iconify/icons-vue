<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="fodc3p52p"/><circle class="cpk0fnbgt"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:karafun" /></template>
<style>
.cpk0fnbgt {
  cx: 24px;
  cy: 24px;
  r: 21.5px;
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

.fodc3p52p {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M15.991 13.308v20.944m11.523-20.607l-8.327 12.448h-3.196m19.85 8.159c-2.145 2.145-3.028 2.44-4.794 2.44c-4.178 0-6.813-10.598-11.86-10.598m-5.028-12.786h3.663m7.608 0h3.663M14.159 34.252h3.663");
}

</style>
