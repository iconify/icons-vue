<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mqygdac9i"/><path class="a72z8yaep"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:clore-background" /></template>
<style>
.a72z8yaep {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.247 5.207a7.6 7.6 0 0 0-3.9-1.205c-1.514 1.41-1.464 4.274 0 5.584c.61-2.415 2.03-3.724 3.9-4.38m1.775 1.36c-2.28-.1-4.05 1.964-4.05 3.973a5.52 5.52 0 0 1 5.874-.3c-.305-1.61-.88-2.459-1.824-3.674m1.974 5.733c-1.42-1.505-4.199-1.355-5.568.05c2.234.54 3.444 1.56 4.453 3.824a6.5 6.5 0 0 0 1.115-3.874m-2.53 5.633c-.15-2.414-1.799-3.833-3.998-3.973c1.134 1.979 1.364 3.823.35 5.838a8.26 8.26 0 0 0 3.649-1.864m-5.823 2.065c1.47-1.46 1.57-3.824 0-5.584c-.605 2.465-1.924 3.725-3.899 4.43c1.36.82 2.25 1.009 3.9 1.154m-5.569-2.564c2.365-.22 3.9-1.76 3.9-4.024c-1.47 1.154-3.95 1.304-5.874.45c.54 1.564.965 2.379 1.975 3.574M4 11.65c1.265 1.355 3.899 1.555 5.569 0c-2.38-.555-3.774-1.95-4.404-3.774A7 7 0 0 0 4 11.65m2.53-5.534c.354 2.415 1.674 3.72 3.998 3.925c-1.174-1.935-1.264-3.775-.4-5.84c-1.674.4-2.554.96-3.599 1.915");
}

.ft5dv1b6b {
  fill: none;
}

.mqygdac9i {
  fill: var(--svg-color--f73737, #f73737);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
