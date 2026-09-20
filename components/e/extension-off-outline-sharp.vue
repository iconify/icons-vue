<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="bwhmmjaje"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:extension-off-outline-sharp" /></template>
<style>
.bwhmmjaje {
  fill: currentColor;
  d: path("m19.116 16.304l-1-1v-.865l.72-.243q.516-.142.84-.627T20 12.442q0-.655-.324-1.143t-.84-.63l-.72-.236V5.769h-4.57l-.115-.853q-.094-.743-.622-1.272q-.528-.528-1.251-.528q-.733 0-1.259.528q-.526.529-.62 1.272l-.116.853h-.982l-1-1H8.68q.16-1.121.962-1.887t1.924-.766q1.1 0 1.9.762q.8.763.965 1.891h4.685v4.947q.842.257 1.363 1.011T21 12.442q0 .93-.521 1.674t-1.363 1.063zM4 20.116V15.45q1.2-.077 2.014-.916t.813-2.092q0-1.13-.823-2.005T4 9.416V4.635l1 1V8.65q1.189.333 2.008 1.397t.819 2.401q0 1.36-.81 2.429q-.81 1.07-2.017 1.363v2.875h13.442l1 1zm16.533 1.844L2.04 3.467l.713-.713l18.492 18.492z");
}

</style>
