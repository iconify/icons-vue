<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#SVGUBkpWdAI)" class="im_ga2w0p"/><path class="mev2d6g4w"/><path class="hvf_34bzq"/><path class="vj1gf7b9p"/><defs><linearGradient id="SVGUBkpWdAI" x1="8.498" x2="16.127" y1="5.003" y2="18.841" gradientUnits="userSpaceOnUse"><stop class="bp3j6lb9w"/><stop offset="1" class="u9epcjs3h"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lyxe" /></template>
<style>
.bp3j6lb9w {
  stop-color: var(--svg-color--e59f9a, #e59f9a);
}

.ft5dv1b6b {
  fill: none;
}

.hvf_34bzq {
  fill: var(--svg-color--dadbda, #dadbda);
  d: path("m9.807 16l-2.283-4h4.526l2.244 4z");
}

.im_ga2w0p {
  d: path("m12 3l8 4.438v9.125L12 21l-8-4.438V7.438z");
}

.mev2d6g4w {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.25 8H9.775L7.5 12h4.576z");
}

.u9epcjs3h {
  stop-color: var(--svg-color--6a3fba, #6a3fba);
}

.vj1gf7b9p {
  fill: var(--svg-color--efeeee, #efeeee);
  d: path("m14.292 15.998l-2.244-3.992L14.25 8l2.248 4z");
}

</style>
