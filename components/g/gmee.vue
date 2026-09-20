<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVG9S36Mcfq)" class="s_n76ac2r"/><defs><linearGradient id="SVG9S36Mcfq" x1="6.195" x2="17.987" y1="18.075" y2="7.786" gradientUnits="userSpaceOnUse"><stop class="ahz_z2bxj"/><stop offset="1" class="vkycpjbso"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gmee" /></template>
<style>
.ahz_z2bxj {
  stop-color: var(--svg-color--5945fc, #5945fc);
}

.ft5dv1b6b {
  fill: none;
}

.s_n76ac2r {
  d: path("M10.75 3h3v1.135c3.26.53 4.76 2.615 5.28 5.365h-3.68c-.495-1.22-1.5-2-3.35-2c-2.465 0-3.75 1.95-3.75 4.505c0 2.56 1.37 4.38 3.75 4.49c2.11.1 3.125-.95 3.53-2.495h-2.78v-2.5h6.49l.01.62c0 3.98-1.25 7.285-5.5 7.81V21h-3v-1.145c-3.83-.675-6-3.675-6-7.735c0-4.075 2.05-7.45 6-8.03z");
}

.vkycpjbso {
  stop-color: var(--svg-color--3d9eef, #3d9eef);
}

</style>
