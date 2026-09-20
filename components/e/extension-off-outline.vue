<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="nb_m5cb_b"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:extension-off-outline" /></template>
<style>
.nb_m5cb_b {
  fill: currentColor;
  d: path("m19.116 16.304l-1-1v-.865l.72-.243q.516-.142.84-.627T20 12.442q0-.655-.324-1.143t-.84-.63l-.72-.236V6.23q0-.212-.126-.337t-.317-.125h-4.127l-.115-.854q-.094-.742-.622-1.27q-.528-.53-1.251-.53q-.733 0-1.259.53q-.526.528-.62 1.27l-.116.854h-.982l-1-1H8.68q.16-1.121.962-1.887q.802-.767 1.924-.767q1.1 0 1.9.763t.965 1.891h3.242q.595 0 1.019.424t.424 1.038v3.485q.842.257 1.363 1.011T21 12.442q0 .93-.521 1.674t-1.363 1.063zm1.417 5.656L2.04 3.467l.713-.713l18.492 18.492zM18.5 19.116l1 1H5.442q-.6 0-1.02-.431Q4 19.254 4 18.654V15.45q1.2-.077 2.014-.916t.813-2.092q0-1.13-.823-2.005T4 9.416v-4.84l1 1V8.65q1.189.333 2.008 1.397t.819 2.401q0 1.36-.81 2.429q-.81 1.07-2.017 1.363v2.414q0 .192.125.327q.125.134.317.134zm-7.484-6.674");
}

</style>
