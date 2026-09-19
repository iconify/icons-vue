<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="vev5wu1ui"><path class="tf5gbdvdl"/><circle class="dy2zipblp"/></g><path class="o_z-wnaas"/><g class="mrjy-p0fq"><ellipse class="ez119wb1d"/><ellipse class="fknqo6ber"/></g><path class="jsmzoqb4u"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:angry-face-with-horns" /></template>
<style>
.dy2zipblp {
  cx: 31.953px;
  cy: 32.02px;
  r: 31.75px;
}

.ez119wb1d {
  cx: 20.92px;
  cy: 31.32px;
  rx: 4.175px;
  ry: 5.063px;
}

.fknqo6ber {
  cx: 42.756px;
  cy: 31.32px;
  rx: 4.176px;
  ry: 5.063px;
}

.jsmzoqb4u {
  fill: var(--svg-color--6e3a84, #6e3a84);
  d: path("M30.942 29.27c-2.579-9.167-11.263-12.188-19.997-12.287c-2.551-.029-3.133 3.951-.545 3.98c7.353.083 14.6 1.932 16.812 9.798c.703 2.495 4.424.978 3.73-1.491m1.96 0c2.578-9.167 11.264-12.188 19.996-12.287c2.552-.029 3.134 3.951.545 3.98c-7.354.083-14.601 1.932-16.812 9.798c-.701 2.495-4.423.978-3.729-1.491m3.914 27.433c-1.037.354-2.072.063-2.313-.646c-.238-.709.407-1.572 1.443-1.923l4.398-1.479c1.035-.352 2.071-.057 2.311.652c.238.707-.407 1.566-1.442 1.914z");
}

.mrjy-p0fq {
  fill: var(--svg-color--25333a, #25333a);
}

.o_z-wnaas {
  fill: var(--svg-color--fff, #fff);
  d: path("M27.373 31.32c0 5.338-2.888 9.663-6.453 9.663c-3.564 0-6.453-4.322-6.453-9.663c0-5.337 2.888-9.663 6.453-9.663s6.453 4.326 6.453 9.663m21.837 0c0 5.338-2.891 9.663-6.453 9.663c-3.564 0-6.453-4.322-6.453-9.663c0-5.337 2.889-9.663 6.453-9.663c3.562 0 6.453 4.326 6.453 9.663");
}

.tf5gbdvdl {
  d: path("M62.55 1.455c-1.463-3.972-6.123 3.02-9.146 6.893c-3.03 3.874-5.779 7.263-2.443 9.869c3.341 2.612 4.366 14.07 7.391 10.194c3.02-3.869 5.836-22.507 4.198-26.956m-61.193 0c1.463-3.973 6.123 3.02 9.147 6.892c3.03 3.874 5.778 7.263 2.443 9.869c-3.341 2.612-4.367 14.07-7.39 10.194c-3.03-3.868-5.837-22.506-4.2-26.955");
}

.vev5wu1ui {
  fill: var(--svg-color--bf84ce, #bf84ce);
}

</style>
