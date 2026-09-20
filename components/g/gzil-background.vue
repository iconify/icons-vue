<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVG7wAOmbEc)" class="r4i437pya"/><path class="toma3fbsc"/><path class="x7djp17nm"/></g><defs><linearGradient id="SVG7wAOmbEc" x1="12.009" x2="12.009" y1="18.428" y2="5.365" gradientUnits="userSpaceOnUse"><stop class="mn57habsj"/><stop offset=".5" class="ezv68tb2y"/><stop offset="1" class="goegiob7s"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:gzil-background" /></template>
<style>
.ezv68tb2y {
  stop-color: var(--svg-color--3f2d87, #3f2d87);
}

.ft5dv1b6b {
  fill: none;
}

.goegiob7s {
  stop-color: var(--svg-color--aa2b87, #aa2b87);
}

.mn57habsj {
  stop-color: var(--svg-color--009c8b, #009c8b);
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.toma3fbsc {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.76 5.412h3.986l.099.009c.988.019 1.976.07 2.95.25c.55.098 1.083.249 1.581.503a2.55 2.55 0 0 1 1.342 1.487c.202.598.282 1.21.282 1.835v.15h-3.294l-.014-.32a1.3 1.3 0 0 0-.043-.234c-.249-.932-1.75-.847-2.498-.857c-1.478 0-2.96 0-4.438.01c-.847.009-1.675.197-2.099 1.007a3.2 3.2 0 0 0-.32 1.336h4.188l-.117.07c-1.356.834-2.645 1.751-4 2.58c-.057.032-.08.07-.07.131c.037.32.056.64.112.956c.061.371.16.696.47.94c.227.175.495.283.777.34a7.7 7.7 0 0 0 1.61.16h3.02c.688 0 1.403-.024 2.085-.132c.645-.108 1.318-.386 1.337-1.144c.019-.404 0-.668 0-1.078H12l.33-.192c1.369-.843 2.95-1.793 4.324-2.63H20v.178c0 .696-.014 1.393-.014 2.094c0 .598-.005 1.195-.066 1.798c-.047.498-.122.997-.282 1.473a2.92 2.92 0 0 1-1.445 1.745a4.9 4.9 0 0 1-1.435.471c-.857.16-1.723.221-2.598.23c-1.162.01-2.325.005-3.482.01c-.82 0-1.638 0-2.452-.085a8.5 8.5 0 0 1-1.553-.273a3.18 3.18 0 0 1-2.381-2.32a8 8 0 0 1-.26-1.623L4 13.844v-3.162l.01-.07c.032-.438.056-.871.103-1.304a6 6 0 0 1 .292-1.374c.282-.786.762-1.407 1.515-1.816c.532-.283 1.101-.433 1.694-.532a15 15 0 0 1 2.024-.17c.047.005.084 0 .122-.004");
}

.x7djp17nm {
  fill: var(--svg-color--fff, #fff);
  d: path("m6.932 13.128l.108-.42c.01-.046.033-.075.08-.098c.81-.377 1.62-.753 2.42-1.144c.992-.489 1.98-.997 2.964-1.496l.419-.207a.1.1 0 0 1 .07-.014l-5.84 3.59c-.075-.06-.14-.122-.22-.178v-.038zm3.138 1.459c2.034-1.261 4.551-2.739 6.589-4c.099.117.024.32.118.442c.028.033.023.094.028.141c.01.08.038.17.005.226c-.033.052-.127.075-.198.108c-2.047.975-4.499 2.104-6.541 3.083");
}

</style>
