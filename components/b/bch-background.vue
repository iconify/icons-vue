<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="a6bww2bfk"/><path class="z5b6puc_d"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:bch-background" /></template>
<style>
.a6bww2bfk {
  fill: var(--svg-color--58be92, #58be92);
  d: path("M24 0H0v24h24z");
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.z5b6puc_d {
  fill: var(--svg-color--fff, #fff);
  d: path("M16.128 7.631c-.616-1.577-2.175-1.72-3.995-1.361L11.49 4l-1.38.4l.634 2.189l-1.097.332l-.633-2.215l-1.367.4l.643 2.247l-.876.27v-.005l-1.893.54l.418 1.464s1.012-.314 1.003-.287c.553-.162.827.112.962.377l.737 2.567l.148-.023l-.148.04l1.033 3.605c.027.18 0 .486-.382.598c.018.009-1.002.292-1.002.292l.198 1.717l1.784-.512l.989-.275l.656 2.279l1.362-.395l-.638-2.252l1.096-.306l.643 2.247l1.38-.395l-.656-2.279c2.27-.795 3.72-1.843 3.303-4.067c-.342-1.789-1.389-2.337-2.787-2.27c.675-.643.967-1.492.517-2.652zm-.512 5.439c.48 1.707-2.49 2.346-3.416 2.62l-.867-3.025c.93-.27 3.77-1.37 4.283.405m-1.86-4.095c.44 1.56-2.05 2.072-2.828 2.297l-.786-2.742c.777-.22 3.146-1.168 3.613.454z");
}

</style>
