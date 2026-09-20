<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="ctf38zbdo"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="material-symbols-light:extension-off" /></template>
<style>
.ctf38zbdo {
  fill: currentColor;
  d: path("M19.116 16.304L7.58 4.769h1.104q.156-1.121.957-1.887q.802-.767 1.916-.767q1.108 0 1.91.767q.801.766.963 1.887h3.242q.594 0 1.018.424t.425 1.038v3.485q.842.257 1.363 1.011T21 12.442q0 .93-.521 1.674t-1.363 1.053zm1.417 5.656L2.04 3.467l.713-.713l18.492 18.492zm-15.09-1.844q-.6 0-1.022-.431Q4 19.254 4 18.654V15.45q1.2-.077 2.014-.916t.813-2.092q0-1.13-.823-2.005T4 9.416v-4.84l15.5 15.539z");
}

</style>
