<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="c52q9tb2h"/><path class="wvjwpwj1y"/><path class="b2kywebwv"/><path class="oz9j3930z"/><path class="rw_li4b5r"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:light-bulb" /></template>
<style>
.b2kywebwv {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M22.707 10.293a1 1 0 0 0-1.414 0L18 13.586l-3.293-3.293a.999.999 0 1 0-1.414 1.414L17 15.414V26a1 1 0 1 0 2 0V15.414l3.707-3.707a1 1 0 0 0 0-1.414");
}

.c52q9tb2h {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M29 11.06c0 6.439-5 7.439-5 13.44c0 3.098-3.123 3.359-5.5 3.359c-2.053 0-6.586-.779-6.586-3.361C11.914 18.5 7 17.5 7 11.06C7 5.029 12.285.14 18.083.14C23.883.14 29 5.029 29 11.06");
}

.oz9j3930z {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("M24 31a2 2 0 0 1-2 2h-8a2 2 0 0 1-2-2v-6h12z");
}

.rw_li4b5r {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M11.999 32a1 1 0 0 1-.163-1.986l12-2a.994.994 0 0 1 1.15.822a1 1 0 0 1-.822 1.15l-12 2a1 1 0 0 1-.165.014m0-4a1 1 0 0 1-.163-1.986l12-2a.995.995 0 0 1 1.15.822a1 1 0 0 1-.822 1.15l-12 2a1 1 0 0 1-.165.014");
}

.wvjwpwj1y {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("M22.167 32.5c0 .828-2.234 2.5-4.167 2.5s-4.167-1.672-4.167-2.5S16.066 32 18 32s4.167-.328 4.167.5");
}

</style>
