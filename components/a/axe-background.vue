<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="ia28skbfa"/><path class="vqtxqcbnd"/><path class="gfk7n8bqp"/><path class="bim-74b2b"/><path class="evx92hztz"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:axe-background" /></template>
<style>
.bim-74b2b {
  fill: var(--svg-color--fff, #fff);
  d: path("m12.016 13.235l4.2 6.765l-1.526-1.52l-2.674-5.25zm-2.565 5.09L7.85 20l4-6.785z");
}

.evx92hztz {
  fill: var(--svg-color--fff, #fff);
  d: path("M8.215 12.045L4 7.775l3.635-3.684l4.33 6.83l4.4-6.83L20 7.775l-4.215 4.27L20 16.315L16.365 20l-4.4-6.85L7.635 20L4 16.315z");
}

.ft5dv1b6b {
  fill: none;
}

.gfk7n8bqp {
  fill: var(--svg-color--fff, #fff);
  d: path("M12.016 10.765L16.215 4L14.69 5.52zM9.45 5.675L7.85 4l4 6.785zm2.47 7.415L7.85 20l4.07-4.27L16.215 20z");
}

.ia28skbfa {
  fill: var(--svg-color--193fe0, #193fe0);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vqtxqcbnd {
  fill: var(--svg-color--fff, #fff);
  d: path("M11.92 10.91L7.85 4l4.07 4.27L16.215 4z");
}

</style>
