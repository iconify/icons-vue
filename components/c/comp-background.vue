<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="c__7up55j"/><path class="uw66w5bmo"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:comp-background" /></template>
<style>
.c__7up55j {
  fill: var(--svg-color--00d395, #00d395);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.uw66w5bmo {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.39 16.472a1.34 1.34 0 0 1-.642-1.145v-2.602a.56.56 0 0 1 .22-.445a.56.56 0 0 1 .62-.038l6.103 3.423a1.12 1.12 0 0 1 .56.966v2.697a.69.69 0 0 1-.518.653a.67.67 0 0 1-.507-.08zm8.74-4.943c.342.2.621.567.621.966v5.472c0 .162-.154.312-.294.39l-1.134.74c-.016.01-.054.017-.072.022V16.08a1.1 1.1 0 0 0-.524-.96L8.25 11.977v-3.43c0-.1.035-.196.085-.281a.557.557 0 0 1 .763-.201zm2.566-4.043a1.12 1.12 0 0 1 .556.968v7.994c0 .164-.09.315-.235.393l-1.266.659v-5.566c0-.393-.156-.756-.492-.958l-5.51-3.257V4.56c0-.1.045-.195.093-.28a.56.56 0 0 1 .764-.203z");
}

</style>
