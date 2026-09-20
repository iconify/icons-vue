<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="a7bw6rgry"/><path class="y_414wksi"/><path class="q0l4jvb9p"/><path class="l81iczs2k"/><circle class="llova7btf"/><path class="k4vk-kbom"/><circle class="ep2cpcbun"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:graduation-cap" /></template>
<style>
.a7bw6rgry {
  fill: var(--svg-color--31373d, #31373d);
  d: path("M24 14H12s-5 6-5 10s11 11 11 11s11-7 11-11s-5-10-5-10");
}

.ep2cpcbun {
  cx: 18px;
  cy: 13px;
  r: 3px;
  fill: var(--svg-color--31373d, #31373d);
}

.k4vk-kbom {
  fill: var(--svg-color--fcab40, #fcab40);
  d: path("M8.001 27a1 1 0 0 1-1-1v-3.958c-.042-.634.187-2.036 1.317-2.884l9.022-7.91a1 1 0 0 1 1.318 1.504l-9.08 7.958C8.974 21.166 9 21.982 9 21.99L9.002 26a1 1 0 0 1-1.001 1");
}

.l81iczs2k {
  fill: var(--svg-color--fcab40, #fcab40);
  d: path("M8 25s-2 2-2 3v6s0 2 2 2s2-2 2-2v-6c0-1-2-3-2-3");
}

.llova7btf {
  cx: 8px;
  cy: 26px;
  r: 3px;
  fill: var(--svg-color--fdd888, #fdd888);
}

.q0l4jvb9p {
  fill: var(--svg-color--394146, #394146);
  d: path("M19.64 1.28c-.901-.704-2.377-.704-3.278 0L1.639 12.776c-.901.704-.901 1.856 0 2.56l14.722 11.495c.901.704 2.377.704 3.278 0l14.723-11.495c.901-.704.901-1.856 0-2.56z");
}

.y_414wksi {
  fill: var(--svg-color--292f33, #292f33);
  d: path("M19.64 1.28c-.901-.704-2.377-.704-3.278 0L1.639 12.776c-.901.704-.901 1.856 0 2.56l14.722 11.495c.902.704 2.377.704 3.278 0l14.722-11.495c.902-.704.902-1.856 0-2.56z");
}

</style>
