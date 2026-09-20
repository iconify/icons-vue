<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path class="q9zmvqa0q"/><path class="clqpvab4h"/><path class="k83ur2bvm"/><path class="dlje1wbxx"/><path class="bonj_pbov"/><path class="aqt3-lbha"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:hxro" /></template>
<style>
.aqt3-lbha {
  fill: var(--svg-color--ff00c8, #ff00c8);
  d: path("M13.13 12.45L21 3.563l-6.778 8.887l2.745 4.612h-4.22l-1.203-1.834l-2.919 2.396l3.307-3.763l1.446 2.076h1.918z");
}

.bonj_pbov {
  fill: var(--svg-color--ff00c8, #ff00c8);
  d: path("M15.183 12.41L21 3.563l-5.5 8.847l2.474 3.848l-.18.686z");
}

.clqpvab4h {
  fill: var(--svg-color--ff00c8, #ff00c8);
  d: path("M12.023 21c-3.144 0-5.72-1.991-6.615-2.981l.855-.912c2.166 1.919 3.161 2.83 6.311 3.195c2.515.293 5.175-1.237 6.176-2.041c-.32.489-2.8 2.739-6.727 2.739");
}

.dlje1wbxx {
  fill: var(--svg-color--02fd05, #02fd05);
  d: path("m12.658 9.384l2.717-2.447l-3.212 3.6l-1.305-1.912H8.946l2.042 3.33L3 21l6.863-9.045L7.208 7.5h4.24l1.216 1.884z");
}

.ft5dv1b6b {
  fill: none;
}

.k83ur2bvm {
  fill: var(--svg-color--02fd05, #02fd05);
  d: path("M8.873 12.14L6.342 7.9l-.26.63l2.352 3.61L3 21z");
}

.q9zmvqa0q {
  fill: var(--svg-color--02fd05, #02fd05);
  d: path("M12.4 3c3.093 0 5.624 2.014 6.507 3.02l-.844.917l-.062-.062c-2.086-1.9-3.082-2.8-6.142-3.166c-2.475-.298-5.062 1.248-6.046 2.064C6.127 5.278 8.535 3 12.399 3");
}

</style>
