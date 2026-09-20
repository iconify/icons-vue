<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<defs><path id="SVG7633XbnN" class="ceivq4hyx"/><path id="SVGuV6MGbXh" class="kx5vrtmtf"/></defs><g class="ft5dv1b6b"><path fill="url(#SVGqz4aPeUi)" clip-rule="evenodd" class="el-rr5bep"/><use href="#SVG7633XbnN"/><path fill="url(#SVGSP67LepA)" class="frmt3nb8w"/><use href="#SVGuV6MGbXh"/><path fill="url(#SVGsIwnbdfw)" class="gub6c3emk"/><path fill="url(#SVGqz4aPeUi)" clip-rule="evenodd" class="el-rr5bep"/><use href="#SVG7633XbnN"/><path fill="url(#SVGSP67LepA)" class="frmt3nb8w"/><use href="#SVGuV6MGbXh"/><path fill="url(#SVGsIwnbdfw)" class="gub6c3emk"/><defs><linearGradient id="SVGqz4aPeUi" x1="6.094" x2="17.906" y1="5.25" y2="19.031" gradientUnits="userSpaceOnUse"><stop class="os9aeqbuw"/><stop offset=".56" class="prdoc61dt"/><stop offset="1" class="cmavuzjzy"/></linearGradient><linearGradient id="SVGSP67LepA" x1="7.5" x2="21.839" y1="5.525" y2="13.542" gradientUnits="userSpaceOnUse"><stop class="cx_xa9jsx"/><stop offset="1" class="d6gvmca8f"/></linearGradient><linearGradient id="SVGsIwnbdfw" x1="5.531" x2="20.156" y1="6.094" y2="14.25" gradientUnits="userSpaceOnUse"><stop class="xg6kiebwj"/><stop offset="1" class="a9bph6ysg"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:ator" /></template>
<style>
.a9bph6ysg {
  stop-color: var(--svg-color--01678d, #01678d);
}

.ceivq4hyx {
  fill: var(--svg-color--005257, #005257);
  d: path("M17.242 15.29a.9.9 0 0 0 .383.085l.383.011c1.096.056 2.716.13 2.964-2.638q.027-.37.028-.748h-2.813a6.2 6.2 0 0 1-.945 3.29M3.45 14.813c.377.338.95.563 1.8.563a6.6 6.6 0 0 0 1.468-.152A6.16 6.16 0 0 1 5.813 12H3c0 .984.158 1.93.45 2.812");
}

.cmavuzjzy {
  stop-color: var(--svg-color--065270, #065270);
}

.cx_xa9jsx {
  stop-color: var(--svg-color--025962, #025962);
}

.d6gvmca8f {
  stop-color: var(--svg-color--026d77, #026d77);
}

.el-rr5bep {
  fill-rule: evenodd;
  d: path("M12 18.188a6.188 6.188 0 1 0 0-12.376a6.188 6.188 0 0 0 0 12.375M12 21a9 9 0 1 0 0-18a9 9 0 0 0 0 18");
}

.frmt3nb8w {
  d: path("M16.433 14.29c1.726.978 4.207.922 4.483-1.041A8.998 8.998 0 0 0 12 3.019a9 9 0 0 0-8.916 10.23c.276 1.963 2.757 2.025 4.483 1.04a8.96 8.96 0 0 1 8.866 0");
}

.ft5dv1b6b {
  fill: none;
}

.gub6c3emk {
  d: path("M17.276 11.466c.405.208.9-.073.821-.518a6.187 6.187 0 0 0-12.206.09c-.073.428.394.703.776.507A11.46 11.46 0 0 1 12 10.313c1.957 0 3.758.382 5.276 1.153m3.64 1.783c-.276 1.963-2.757 2.025-4.483 1.04a8.96 8.96 0 0 0-8.866 0c-1.726.98-4.207.923-4.483-1.04a9 9 0 1 1 17.832 0");
}

.kx5vrtmtf {
  fill: var(--svg-color--005560, #005560);
  d: path("M8.062 12c-1.8-.45-3.375-2.813-3.937-3.937v2.53l2.25 3.095z");
}

.os9aeqbuw {
  stop-color: var(--svg-color--025a63, #025a63);
}

.prdoc61dt {
  stop-color: var(--svg-color--026e7a, #026e7a);
}

.xg6kiebwj {
  stop-color: var(--svg-color--02bfc5, #02bfc5);
}

</style>
