<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGcZQmRbte)" class="r4i437pya"/><path class="m_bdfpbzy"/><path class="x_nnj1h2o"/><path class="r6p9rc7jn"/><path class="zesre1b2v"/></g><defs><linearGradient id="SVGcZQmRbte" x1="6.813" x2="16.515" y1="6.312" y2="17.229" gradientUnits="userSpaceOnUse"><stop class="tzqypg7gr"/><stop offset="1" class="wp7m43fks"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cph-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.m_bdfpbzy {
  fill: var(--svg-color--fff, #fff);
  d: path("m9.176 7.72l1.05.292v3.902c.047.447.404 1.492 1.43 2.113l2.542 1.535v1.27l-3.827-2.353a2.87 2.87 0 0 1-1.195-2.4V7.715zm-1.68-.48l.875.25a4 4 0 0 0-.023.414v5.116c.047.447.414 1.492 1.459 2.113l.917.546l-1.13.565l-1.096-.659a2.86 2.86 0 0 1-1.214-2.4v-4.9c0-.254.052-.635.212-1.05zm6.702 10.52l-2.66-1.596l-1.129.579l2.532 1.534c.203.123.4.198.584.245l.678-.715v-.047z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.r6p9rc7jn {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.168 5.634v.16c.48-.212 1.237-.024 1.558.099l4.725 2.824A3.26 3.26 0 0 1 16 10.9v5.296a4.13 4.13 0 0 1-.744 2.306l.047.094c1.412-.72 1.878-2.165 1.873-2.8V10.73a3 3 0 0 0-1.374-2.48l-4.594-2.79a2.1 2.1 0 0 0-1.2-.311c-.913 0-1.61.325-1.84.485");
}

.tzqypg7gr {
  stop-color: var(--svg-color--262223, #262223);
}

.wp7m43fks {
  stop-color: var(--svg-color--6b6a6f, #6b6a6f);
}

.x_nnj1h2o {
  fill: var(--svg-color--fff, #fff);
  d: path("M4.94 9.335v4.824a3.6 3.6 0 0 0 1.722 3.074l3.747 2.306a3.04 3.04 0 0 0 4.242-1.058a3.04 3.04 0 0 0 .408-1.554v-2.372l-1.177.626v1.868a1.8 1.8 0 0 1-1.842 1.832a1.8 1.8 0 0 1-.916-.274l-3.6-2.212a2.95 2.95 0 0 1-1.408-2.518V9.274a1.84 1.84 0 0 1 2.82-1.554l3.577 2.231a2.96 2.96 0 0 1 1.37 2.556v1.648l1.176-.645v-1.554c0-1.044-.47-2.014-1.365-2.565L9.496 6.812a2.984 2.984 0 0 0-4.557 2.523");
}

.zesre1b2v {
  fill: var(--svg-color--fff, #fff);
  d: path("M10.169 4.65v-.16a3.5 3.5 0 0 1 1.845-.484c.188-.023.697.01 1.2.31l2.01 1.224l-1.167.603l-2.325-1.393c-.32-.123-1.083-.31-1.563-.1m4.73 1.997l1.553.927a3.01 3.01 0 0 1 1.431 2.184v5.295c0 1.096-.39 1.995-.626 2.306l.047.094c1.417-.72 1.76-2.165 1.756-2.8V9.588a2.96 2.96 0 0 0-1.257-2.48l-1.727-1.05z");
}

</style>
