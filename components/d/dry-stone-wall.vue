<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="c7o1tcbhr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix:dry-stone-wall" /></template>
<style>
.c7o1tcbhr {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  stroke-width: var(--svg-stroke-width--1-5px, 1.5px);
  d: path("M2.5 17.25v-1.849A1.68 1.68 0 0 1 3.25 14l.242-.161a1.75 1.75 0 0 1 1.116-.288l.892.074a1.636 1.636 0 0 1 1.5 1.63v1.995A1.75 1.75 0 0 1 5.25 19h-1a1.75 1.75 0 0 1-1.75-1.75m7.25 0v-2.064a1.645 1.645 0 0 1 1.125-1.561l.481-.16a1.75 1.75 0 0 1 1.264.061l.591.262a1.75 1.75 0 0 1 1.039 1.599v1.863A1.75 1.75 0 0 1 12.5 19h-1a1.75 1.75 0 0 1-1.75-1.75m7.25 0v-1.975a1.555 1.555 0 0 1 1.25-1.525l.661-.132a1.75 1.75 0 0 1 1.126.151l.496.247a1.75 1.75 0 0 1 .967 1.566v1.668A1.75 1.75 0 0 1 19.75 19h-1A1.75 1.75 0 0 1 17 17.25M4.5 8.75V7.375a1.75 1.75 0 0 1 .7-1.4l.684-.513a1.75 1.75 0 0 1 1.373-.32l1.816.34a1.75 1.75 0 0 1 1.427 1.72V8.75a1.75 1.75 0 0 1-1.75 1.75h-2.5A1.75 1.75 0 0 1 4.5 8.75m8.75 0V7.226a1.75 1.75 0 0 1 1.152-1.645l1.005-.365a1.75 1.75 0 0 1 1.187-.004l1.745.623A1.75 1.75 0 0 1 19.5 7.483V8.75a1.75 1.75 0 0 1-1.75 1.75H15a1.75 1.75 0 0 1-1.75-1.75");
}

</style>
