<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="pe4ako5xm"/><path class="f2jtpl28b"/><path class="vex57jb0r"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:lusd-background" /></template>
<style>
.f2jtpl28b {
  fill: var(--svg-color--fff, #fff);
  d: path("M13.5 20c3.697-.706 6.5-4.097 6.5-8s-2.803-7.151-6.5-7.857v2.119c.754.304 1.485.913 2.142 2.052c0 .069-1.33.98-1.959 1.405c-.776-1.877-1.982-1.896-2.483-1.22c-.717.967.536 1.608 1.971 2.144c1.624.605 2.852 2.035 2.83 3.857c-.023 1.782-1.296 2.716-2.5 3.175z");
}

.ft5dv1b6b {
  fill: none;
}

.pe4ako5xm {
  fill: var(--svg-color--2eb6ea, #2eb6ea);
  d: path("M24 0H0v24h24z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.vex57jb0r {
  fill: var(--svg-color--fff, #fff);
  d: path("M11 4H4v8.144c.072 4.025 3.084 7.385 7 7.856v-2.265c-1.356-.323-2.677-1.341-2.831-3.45l2.235-.649c-.014.696.285 2.085 1.597 2.076c1.311-.008 1.596-.955 1.575-1.426c.05-.31-.195-1.058-1.575-1.586c-1.725-.66-3.279-1.916-3.279-3.62c0-1.836 1.103-2.53 2.278-2.88z");
}

</style>
