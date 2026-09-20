<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="suwa2jbvo"/><path class="mvko4-z7m"/><path class="vepudcb0f"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aave-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.mvko4-z7m {
  fill: var(--svg-color--fff, #fff);
  d: path("M9.876 16c.899 0 1.627-.698 1.627-1.56s-.728-1.56-1.627-1.56s-1.627.698-1.627 1.56S8.977 16 9.876 16m4.254 0c.898 0 1.627-.698 1.627-1.56s-.729-1.56-1.628-1.56s-1.627.698-1.627 1.56s.729 1.56 1.627 1.56");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.suwa2jbvo {
  fill: var(--svg-color--9391f7, #9391f7);
  d: path("M24 0H0v24h24z");
}

.vepudcb0f {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 8c-4.419 0-8.001 3.5-8 7.815h2.044c0-3.234 2.645-5.856 5.956-5.856c3.31 0 5.956 2.622 5.956 5.856H20C20 11.5 16.418 8 12 8");
}

</style>
