<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path fill="url(#SVGgvX0Defq)" class="r4i437pya"/><path class="k0a-8zo1y"/><path class="p-1tk-b5f"/><path clip-rule="evenodd" class="a_qcezg4a"/></g><defs><linearGradient id="SVGgvX0Defq" x1="20" x2="5.404" y1="11.795" y2="11.795" gradientUnits="userSpaceOnUse"><stop class="b-_xi0xsx"/><stop offset=".28" class="dwucvybgx"/><stop offset=".56" class="s1rb3dbaa"/><stop offset=".8" class="rt_jp2bva"/><stop offset="1" class="rgle654dl"/></linearGradient><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:domi-background" /></template>
<style>
.a_qcezg4a {
  fill: var(--svg-color--fff, #fff);
  fill-rule: evenodd;
  d: path("M12 19.059a7.06 7.06 0 1 0 0-14.12a7.06 7.06 0 0 0 0 14.12M12 20a8 8 0 1 0 0-16a8 8 0 0 0 0 16");
}

.b-_xi0xsx {
  stop-color: var(--svg-color--f3d856, #f3d856);
}

.dwucvybgx {
  stop-color: var(--svg-color--f8ee5d, #f8ee5d);
}

.ft5dv1b6b {
  fill: none;
}

.k0a-8zo1y {
  fill: var(--svg-color--fff, #fff);
  d: path("M5.883 8.471c-.377-.188-.626-.706-.706-.941c.564.376 1.962.47 2.588.47a3 3 0 0 0-.706.471c.565-.188 1.492-.235 1.882-.235a3.77 3.77 0 0 1 2.824 1.176c-.377.565-.47 1.332-.47 1.647c-.133-.941-.942-2.353-2.354-2.353c-1.13 0-1.882.786-2.117 1.177l.47-.236v4c-.188 0-.39-.155-.47-.235c.376.941 1.411 1.412 2.117 1.412c.79 0 1.337-.325 1.709-.767c.705-.847.734-1.967.927-2.998c.338-1.835 1.6-2.823 3.482-2.823s3.53 1.411 3.53 3.294c0 2.447-1.177 3.765-3.53 3.765c-1.318 0-2.353-.706-2.823-1.412c.376-.377.625-1.257.705-1.647c.236.705.942 2.117 2.118 2.117c1.412 0 2.118-.94 2.118-3.171c0-1.789-1.177-2.476-2.118-2.476c-1.412 0-2.259 1.309-2.47 2.476c-.114.611-.198 1.336-.354 1.76c-.94 2.588-3.058 2.352-4.47 2.352c-1.13 0-1.727.942-1.882 1.412z");
}

.p-1tk-b5f {
  fill: var(--svg-color--fff, #fff);
  d: path("M7.294 9.342v-.4l-.47.235c-.236-.235-.236-.47-.236-.706L5.177 7.53c.08.235.33.753.706.941v8.235c.155-.47.752-1.412 1.882-1.412h.33c1.148.015 2.625.034 3.595-1.303l.16-.235a5 5 0 0 0 .31-.617l-.395-.197c-.235.626-1.035 1.929-2.353 2.117c-1.318.189-2.273-.235-2.588-.47l-.094-.236l.329-.235h-.47c-.189-.565-.189-1.13 0-.941c.188.188.39.235.47.235c0-.188-.315-.55-.47-.706V10.59s-.236-.236-.236-.471c0-.376.315-.155.47 0l.236-.353l-.235.118a2.4 2.4 0 0 1 .47-.541m7.962 5.004c1.28-.09 1.92-1.045 1.92-3.167c0-1.788-1.176-2.475-2.117-2.475c-.08 0-.16 0-.236.014v-.014c1.648-.236 3.295.94 3.295 2.823c0 2.588-1.647 3.294-2.824 3.294zm.038.943l-.235.005c-1.318 0-2.353-.706-2.824-1.412h.706c.235.315 1.035.94 2.353.94z");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.r4i437pya {
  d: path("M24 0H0v24h24z");
}

.rgle654dl {
  stop-color: var(--svg-color--805321, #805321);
}

.rt_jp2bva {
  stop-color: var(--svg-color--f7ee5d, #f7ee5d);
}

.s1rb3dbaa {
  stop-color: var(--svg-color--c8742a, #c8742a);
}

</style>
