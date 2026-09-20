<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="zu4q6zb9a"/><path class="ip42ldnfi"/><path class="j6kzdibxo"/><path class="kpajb96kg"/><path class="e1g6y3dka"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ethm" /></template>
<style>
.e1g6y3dka {
  fill: var(--svg-color--66aa91, #66aa91);
  d: path("m12 20.999l5.684-9.01L12 14.372z");
}

.ft5dv1b6b {
  fill: none;
}

.ip42ldnfi {
  fill: var(--svg-color--66aa91, #66aa91);
  d: path("m12 7.5l5.684 3.24L12 3z");
}

.j6kzdibxo {
  fill: var(--svg-color--2a9e77, #2a9e77);
  d: path("m12 8.746l-5.684 3.268L12 14.43z");
}

.kpajb96kg {
  fill: var(--svg-color--44a47f, #44a47f);
  d: path("m12 21l-5.684-9.01L12 14.374zm0-12.254l5.684 3.264L12 14.425z");
}

.zu4q6zb9a {
  fill: var(--svg-color--44a47f, #44a47f);
  d: path("m12 7.5l-5.684 3.24L12 3z");
}

</style>
