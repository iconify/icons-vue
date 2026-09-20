<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<path class="hl4x4oxnw"/><path class="dro43zbeo"/><circle transform="rotate(-46.945 52.86 76.09)" class="wxv__eb5a"/><circle transform="rotate(-46.945 95.56 84.858)" class="ck6pgdbol"/><path class="lap2s1b4g"/><path class="g3_mqp6yy"/><path class="pjygg0b1d"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:airplane-arrival" /></template>
<style>
.ck6pgdbol {
  cx: 95.6px;
  cy: 84.9px;
  r: 3.5px;
  fill: var(--svg-color--78a3ad, #78a3ad);
}

.dro43zbeo {
  fill: var(--svg-color--0f6da0, #0f6da0);
  d: path("M76.5 67.4L50.7 35.8c-.9-1.1-2-2.1-3.3-2.8c-2-1.2-4.3.8-3.5 3l7.7 21z");
}

.g3_mqp6yy {
  fill: var(--svg-color--48c0e5, #48c0e5);
  d: path("M9.2 34.2c-.1-1.1 1-2 2-1.6c13.6 4.5 88.1 28.8 95.6 31.1c8.3 2.6 9.5 9.8 9.8 12.4s2.8 3.3 2.4 5.8c-.4 2.4-4.4 6.2-20.9.7C80.4 76.7 44 64.6 36.7 62c-6.9-2.5-25.8-12.9-27.5-27.8");
}

.hl4x4oxnw {
  fill: var(--svg-color--757f3f, #757f3f);
  d: path("M128 117.2c0 1.5-1.2 2.7-2.7 2.7H2.6c-1.5 0-2.7-1.2-2.7-2.7s1.2-2.7 2.7-2.7h122.7c1.5 0 2.7 1.2 2.7 2.7");
}

.lap2s1b4g {
  fill: var(--svg-color--0f6da0, #0f6da0);
  d: path("M109.6 73.9s-2.7 3.1-9.3-.3c-1.1-.5-2.8 3.3-2.1 4c.9.8 14 6.6 17.1 3.1c-1.3-3-5.7-6.8-5.7-6.8");
}

.pjygg0b1d {
  fill: var(--svg-color--0f6da0, #0f6da0);
  d: path("M73.3 74.1c.4 0 .8-.3.9-.7c.4-1.4.7-4.9-2.9-8.2c-3.7-3.5-18.6-6.7-25.1-8.3c-1-.2-1.8.7-1.5 1.6c.4 1.4-.4 2.9-1.8 3.4L19 69.4c-1.4.5-1.8 2.3-.7 3.3l1 .9c2 1.9 4.8 2.9 7.6 2.7zM18.9 42c-2.4-.9-5.3-2.2-6.8-2.7c-.4-.1-.8-.2-1.2-.1l-6.2 4c-1.6.9-.9 3.3.9 3.3l13.8-1.6c1.5-.3 1.7-2.1-.5-2.9m8.1-3.6c.7-1.2-4.1-5-6.3-10.1c-2.9-6.6-4.2-10.6-5.5-13.9c-.7-1.8-3-1.6-3.2.4l-2.7 19c-.1.5.3 1 .8 1.1c-.1 0 10.7 2.9 16.9 3.5m89.9 38.7s-3.2.7-8.2-.7c-1.2-.3-1.9-1.6-1.5-2.8c.3-1 1.3-1.6 2.4-1.5c.9.1 1.9.3 2.6.3c1.9.1 3.7-.1 3.7-.1s.5 2 1 4.8");
}

.wxv__eb5a {
  cx: 52.9px;
  cy: 76.1px;
  r: 3.5px;
  fill: var(--svg-color--78a3ad, #78a3ad);
}

</style>
