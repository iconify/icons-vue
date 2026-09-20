<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGTdqgWd4A)" class="r4i437pya"/><path class="bjf9opkmf"/></g><defs><linearGradient id="SVGTdqgWd4A" x1="5.074" x2="20.619" y1="7.85" y2="13.787" gradientUnits="userSpaceOnUse"><stop class="y8cnyebmq"/><stop offset="1" class="f5rrk2bzu"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:igu-background" /></template>
<style>
.bjf9opkmf {
  fill: var(--svg-color--000, #000);
  d: path("M12 19.998a7.998 7.998 0 0 0 7.918-9.142l-1.811 1.468a6.117 6.117 0 0 1-12.22-.094l-.145-.005l-1.661-1.36a8 8 0 0 0 7.918 9.133m4.366-12.703l2.79 1.129A8 8 0 0 0 7.11 5.67l3.18.363l.189.042a6.13 6.13 0 0 1 5.27 1.091l.616.132zm-6.832 6.869c-1.487-2.155-3.957-4.15-5.011-4.884c-.07-.061-.212-.235-.198-.428c0-1.435 2.052-2.047 3.365-2.047c.752 0 1.27.08 1.717.146c.33.047.616.094.931.094c.363 0 .857-.08 1.355-.155c.518-.08 1.04-.16 1.436-.16c.62 0 1.091.278 1.246.414c-.894.094-1.882.395-2.267.536c.362.123.672.428.785.565c2.287-.795 3.953-.146 4.494.278a9 9 0 0 0-3.576.771l.564.518c1.576-.452 2.527-.052 2.805.207c-.636.047-1.506.258-1.864.362c.65.339 1.958 1.016 1.995 1.016c.24 2.527-1.2 3.02-2.827 3.035c-1.534.014-1.784.71-2.005 1.332l-.037.117c-.189.518-.236 1.614-.236 2.099c-.263-1.144-.823-3.675-.922-4.611c-.108-1.035.31-1.125.682-1.205l.142-.033c.395-.108.832-.527.658-1.082a2.26 2.26 0 0 0-.593-.922c.683 1.331.31 1.458-.376 1.689c-.118.042-.25.085-.381.141c-.908.367-.678 1.915-.621 2.296c.047.301.423 1.859.611 2.598c-1.383.268-1.81-.74-2.009-1.19c-.155-.363-.574-1.412-.762-1.888c.301.08.725.292.894.386zM7.977 7.389a3.2 3.2 0 0 0-1.097.108a.94.94 0 0 0 .95.73c.368 0 .669-.311.772-.471l-.625-.372z");
}

.f5rrk2bzu {
  stop-color: var(--svg-color--00eed4, #00eed4);
}

.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.y8cnyebmq {
  stop-color: var(--svg-color--00b1d3, #00b1d3);
}

</style>
