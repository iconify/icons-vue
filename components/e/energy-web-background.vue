<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="uu3fl3wbt"/><path class="tpze2dbwj"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:energy-web-background" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.tpze2dbwj {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 4a8 8 0 1 0 0 16a8 8 0 0 0 0-16m-.36 11.942a2.6 2.6 0 0 1-1.49.488c-.924 0-1.771-.5-2.413-1.425a5.7 5.7 0 0 1-.926-2.966a.1.1 0 0 1 .065-.09l.63-.283a.094.094 0 0 1 .129.052c0 .012.012.025.012.037c0 1.05.283 2.042.784 2.775c.475.694 1.092 1.066 1.734 1.066c.347 0 .687-.102.976-.296a.106.106 0 0 1 .128.026c.128.167.257.321.397.475a.14.14 0 0 1-.026.141m4.636-.937c-.63.912-1.49 1.425-2.413 1.425c-.924 0-1.773-.513-2.414-1.425c-.603-.873-.937-2.03-.937-3.253c0-1.129.655-2.015 1.476-2.015c.822 0 1.478.886 1.478 2.015a5.85 5.85 0 0 1-.681 2.826a.09.09 0 0 1-.093.05a.1.1 0 0 1-.035-.011c-.013 0-.013-.014-.026-.026c-.077-.09-.155-.18-.219-.27a3 3 0 0 1-.21-.346a.11.11 0 0 1 0-.09c.292-.678.44-1.408.438-2.145c0-.552-.283-1.182-.656-1.182c-.372 0-.655.63-.655 1.182c0 1.05.283 2.042.784 2.774c.476.693 1.092 1.065 1.734 1.065s1.259-.385 1.733-1.065c.5-.734.784-1.72.784-2.774s-.281-2.037-.784-2.771a2.8 2.8 0 0 0-.514-.579a.12.12 0 0 1-.013-.14c.013-.014.027-.026.04-.026l.629-.283a.08.08 0 0 1 .105.025q.24.245.438.525c.603.873.936 2.03.936 3.253s-.322 2.388-.925 3.261");
}

.uu3fl3wbt {
  fill: var(--svg-color--a466ff, #a466ff);
  d: path("M24 0H0v24h24z");
}

</style>
