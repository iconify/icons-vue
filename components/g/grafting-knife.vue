<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="cel8j5bib"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:grafting-knife" /></template>
<style>
.cel8j5bib {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("m8.47 11.97l8.5-8.5q1.515-1.516 3.267-.932q1.988.663 1.498 3.109q-1.599 7.197-9.829 10.007L6.03 21.53q-1.78 1.781-3.56 0t0-3.56zM10.439 15L9 13.561L3.53 19.03q-.719.72 0 1.44q.72.719 1.44 0z");
}

</style>
