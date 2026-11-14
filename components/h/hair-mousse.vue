<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<path class="eeqbg1bsn"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="uix-solid:hair-mousse" /></template>
<style>
.eeqbg1bsn {
  fill: currentColor;
  fill-rule: evenodd;
  d: path("M5.986 10.796q-1.77-1.666-.827-3.907Q5.955 5 7.806 4.776q.208-1.3 1.189-2.281Q10.24 1.25 12 1.25t3.005 1.245q.981.981 1.189 2.281q1.851.224 2.647 2.113q.943 2.241-.827 3.907q-.104.098-.237.151q-.134.053-.277.053h-1.338q.088.294.088.625q0 .409-.135.763q1.06.277 1.89 1.107Q19.25 14.74 19.25 16.5V18q0 1.76-1.245 3.005T15 22.25H9q-1.76 0-3.005-1.245T4.75 18v-1.5q0-1.76 1.245-3.005q.83-.83 1.89-1.107q-.135-.354-.135-.763q0-.34.054-.625H6.5q-.143 0-.277-.053q-.133-.053-.237-.151");
}

</style>
