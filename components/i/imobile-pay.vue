<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<path class="q7set016l"/><path class="ng18r2hkq"/><path class="i44ku9r8n"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:imobile-pay" /></template>
<style>
.i44ku9r8n {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M25.38 40.83c-3.562-4.571 7.713-24.142 1.812-24.142c-5.107 0-12.232 6.378-12.043 8.455c.104 1.138 2.98-1.128 5.155-.951s.228 11.51-4.477 19.092M31.242 7.498c-2.417 0-5.464 3.41-5.464 5.536c0 1.46.688 1.93 1.407 1.93c1.984 0 6.017-1.784 6.017-5.387c0-.746-.29-2.079-1.96-2.079");
}

.ng18r2hkq {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M24.814 36.21c5.749-2.046 11.807-7.014 16.812-17.425m-21.944-8.526c-7.328 8.845-9.467 11.743-9.467 18.886s5.003 8.282 7.419 8.282q.525 0 1.066-.028");
}

.q7set016l {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M33.783 4.5c-12.975 0-27.71 17.226-27.71 28.644c0 7.837 3.693 10.356 7.558 10.356c10.369 0 28.295-7.591 28.295-28.916c0-4.003-1.38-10.084-8.143-10.084");
}

</style>
