<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="w-g0d7oda"/><path class="jo75ubb2u"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hyper-evm-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.jo75ubb2u {
  fill: var(--svg-color--50d2c1, #50d2c1);
  d: path("M20 11.942a9 9 0 0 1-.8 3.795c-.772 1.72-2.62 3.127-4.309 1.63c-1.377-1.22-1.632-3.698-3.695-4.06c-2.729-.333-2.795 2.854-4.578 3.214c-1.987.407-2.646-2.96-2.617-4.488c.03-1.529.433-3.678 2.16-3.678c1.987 0 2.121 3.031 4.644 2.867c2.498-.172 2.542-3.325 4.174-4.675c1.408-1.166 3.065-.311 3.894 1.093c.769 1.298 1.107 2.822 1.124 4.302z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.w-g0d7oda {
  fill: var(--svg-color--072723, #072723);
  d: path("M24 0H0v24h24z");
}

</style>
