<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="beaf9ac8r"/><path fill="url(#SVG8M5aFc8C)" class="i8zldfbib"/></g><defs><linearGradient id="SVG8M5aFc8C" x1="12" x2="12" y1="4.472" y2="19.529" gradientUnits="userSpaceOnUse"><stop offset=".18" class="kyp06bb9s"/><stop offset="1" class="e95_u4b1u"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:glq-background" /></template>
<style>
.beaf9ac8r {
  fill: var(--svg-color--fff, #fff);
  d: path("M24 0H0v24h24z");
}

.e95_u4b1u {
  stop-color: var(--svg-color--5619ed, #5619ed);
}

.ft5dv1b6b {
  fill: none;
}

.i8zldfbib {
  d: path("M15.793 19.528H9.197a1.88 1.88 0 0 1-1.61-.94l-3.34-5.67a1.75 1.75 0 0 1 0-1.793l3.34-5.754a1.77 1.77 0 0 1 1.567-.9h6.64c.658 0 1.317.368 1.646.942l2.4 4.117a.134.134 0 0 1 0 .165c0 .042-.047.08-.085.122l-.828.447a1.826 1.826 0 0 1-2.47-.65l-1.318-2.32h-2.667v9.411h2.663l1.364-2.4l-2.272-1.307a1.5 1.5 0 0 1-.814-1.261V9.53c0-.08.042-.122.08-.16c.084-.042.127-.042.207 0l5.561 3.1a1.38 1.38 0 0 1 .701.894c.08.372.038.777-.17 1.144l-2.39 4.084a1.78 1.78 0 0 1-1.609.936m-6.596-.47h6.596c.537 0 1.035-.221 1.318-.673l2.4-4.08a.96.96 0 0 0 .117-.813a1 1 0 0 0-.494-.66l-1.11-.61l-4.14-2.325v1.835c0 .372.305.739.634.94l2.433 1.389c.08.042.122.165.08.282l-1.525 2.715c-.042.085-.169.118-.211.118h-3.059c-.122 0-.235-.094-.235-.217V7.083c0-.122.104-.259.226-.259h3.068c.084 0 .17.076.211.118l1.365 2.428a1.46 1.46 0 0 0 1.934.527l.658-.367l-2.305-3.915a1.65 1.65 0 0 0-1.365-.673H9.16c-.499 0-.95.184-1.2.63l-3.34 5.755a1.39 1.39 0 0 0 0 1.388l3.34 5.67c.25.452.706.673 1.238.673m.428-1.986l-2.983-4.93a.26.26 0 0 1 0-.245l3.03-4.936c.042-.08.122-.122.245-.08c.084.038.202.122.202.202v9.91c0 .24-.433.211-.494.08M7.145 12l2.503 4.06V7.94z");
}

.kyp06bb9s {
  stop-color: var(--svg-color--9922e6, #9922e6);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

</style>
