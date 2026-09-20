<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGde1AEdHM" x1="500" x2="500" y1="0" y2="992.583" gradientUnits="userSpaceOnUse"><stop offset="0%" class="od14k4bxt"/><stop offset="100%" class="n-o4sdbun"/></linearGradient></defs><path class="lyx2s1aki"/><g transform="translate(11 11)scale(.019)" class="bi12bsetm"><circle fill="url(#SVGde1AEdHM)" class="lmk2kobiz"/><path class="q_l6jobnu"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-telegram" /></template>
<style>
.bi12bsetm {
  fill: none;
  fill-rule: evenodd;
}

.lmk2kobiz {
  cx: 500px;
  cy: 500px;
  r: 500px;
}

.lyx2s1aki {
  fill: var(--svg-color--1a739f, #1a739f);
  d: path("M27.5 5.5h-9.3l-2.1 4.2H4.4v16.8h25.2v-21Zm0 4.2h-8.2l1.1-2.1h7.1Z");
}

.n-o4sdbun {
  stop-color: var(--svg-color--229ed9, #229ed9);
}

.od14k4bxt {
  stop-color: var(--svg-color--2aabee, #2aabee);
}

.q_l6jobnu {
  fill: var(--svg-color--fff, #fff);
  d: path("M226.328 494.722q218.64-95.258 291.59-125.6c138.855-57.755 167.707-67.787 186.513-68.118c4.137-.073 13.385.952 19.375 5.813c5.059 4.104 6.45 9.649 7.117 13.54s1.495 12.757.836 19.684c-7.525 79.061-40.084 270.924-56.648 359.474c-7.009 37.47-20.81 50.033-34.17 51.262c-29.036 2.672-51.085-19.189-79.208-37.624c-44.006-28.847-68.867-46.804-111.583-74.953c-49.366-32.531-17.364-50.411 10.77-79.631C468.281 550.92 596.214 434.556 598.69 424c.31-1.32.597-6.241-2.326-8.84c-2.924-2.598-7.239-1.71-10.353-1.003q-6.62 1.503-210.902 139.4q-29.933 20.553-54.223 20.028c-17.853-.386-52.194-10.094-77.723-18.393c-31.313-10.178-56.2-15.56-54.032-32.846q1.692-13.505 37.196-27.624");
}

</style>
