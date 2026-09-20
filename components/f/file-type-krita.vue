<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVG1mG4IbVQ" gradientUnits="userSpaceOnUse"/><linearGradient id="SVG6mgojcMx" x1="1328" x2="1325" y1="231" y2="90" gradientTransform="rotate(89 1092 -2)scale(1 -1)" href="#SVG1mG4IbVQ"><stop offset="0" class="xzjq9b1nl"/><stop offset="1" class="hvvcpqbhp"/></linearGradient><linearGradient id="SVG8SKFkeVw" x1="112" x2="712" y1="512" y2="512" gradientTransform="translate(-1211 -699)" href="#SVG1mG4IbVQ"><stop offset="0" class="fbeq_z80i"/><stop offset="1" class="dom_6-_hg"/></linearGradient><linearGradient id="SVGCtjK2bex" gradientTransform="translate(-325 187)" href="#SVG8SKFkeVw"><stop offset="0" class="durztpqia"/><stop offset="1" class="f-urg-5hd"/></linearGradient><linearGradient id="SVGVNIXjcaJ" gradientTransform="translate(0 -1024)" href="#SVG8SKFkeVw"><stop offset="0" class="sme2lnb3r"/><stop offset="1" class="od5izhd7v"/></linearGradient></defs><g transform="translate(.8 -.8)scale(.032)"><circle class="f4p2sjblx"/><circle fill="url(#SVG8SKFkeVw)" transform="rotate(210)" class="cpligrb1g"/><circle fill="url(#SVGCtjK2bex)" transform="rotate(-30)" class="uu1mk7b_q"/><circle fill="url(#SVGVNIXjcaJ)" transform="rotate(90)" class="um_p4ebmd"/></g><path class="pn7-59qfj"/><path class="gnvblrb9j"/><path fill="url(#SVG6mgojcMx)" transform="translate(-125.6 -5)scale(.112)" class="oej1dbbnb"/><path class="uvw5lff_k"/><path class="u0qwbabyc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-krita" /></template>
<style>
.cpligrb1g {
  cx: -699px;
  cy: -187px;
  r: 400px;
}

.dom_6-_hg {
  stop-color: var(--svg-color--ff0, #ff0);
  stop-opacity: 0;
}

.durztpqia {
  stop-color: var(--svg-color--0ff, #0ff);
}

.f-urg-5hd {
  stop-color: var(--svg-color--0ff, #0ff);
  stop-opacity: 0;
}

.f4p2sjblx {
  cx: 512px;
  cy: 512px;
  r: 400px;
  fill: var(--svg-color--fff, #fff);
}

.fbeq_z80i {
  stop-color: var(--svg-color--ff0, #ff0);
}

.gnvblrb9j {
  fill: var(--svg-color--404040, #404040);
  d: path("M18.7 16.5c-2 2-6-1.1-7.7-3l-8.6-9Q1.6 3.7 2 3q.6-.6 1.5 0c.6.4 8.3 5.3 10.6 6.6s6 4.4 4.6 6.9");
}

.hvvcpqbhp {
  stop-color: var(--svg-color--5596ea, #5596ea);
  stop-opacity: 0;
}

.od5izhd7v {
  stop-color: var(--svg-color--f0f, #f0f);
  stop-opacity: 0;
}

.oej1dbbnb {
  d: path("M1317 209a85 85 0 0 1-139-19c6 37 30 70 68 82c28 10 73 10 93-27z");
}

.pn7-59qfj {
  fill-opacity: var(--svg-fill-opacity--0-5, 0.5);
  d: path("M8 6.7L6 9.2C8 11 10 13 10.9 14c1.4 1.5 4.3 3.7 6.4 3.4c.8.6 2.7 2 3.4 2.2l.1 1c.6 1.6 2.8 2.7 1.5 4.5c2.6-1.6 3.2-4.2 2.2-6q-1.2-1.6-2.5-1.2c-.5-.6-2.4-2.2-3.1-2.8c-.5-2-3.2-4.2-5-5z");
}

.sme2lnb3r {
  stop-color: var(--svg-color--f0f, #f0f);
}

.u0qwbabyc {
  fill: var(--svg-color--282828, #282828);
  d: path("M22.2 25c2.6-1.5 3.4-4 2.4-6c-.8-1.4-2.2-1.7-3-1s-1 1.6-.8 2.4c.6 1.7 2.8 2.8 1.4 4.6");
}

.um_p4ebmd {
  cx: 512px;
  cy: -512px;
  r: 400px;
}

.uu1mk7b_q {
  cx: 187px;
  cy: 699px;
  r: 400px;
}

.uvw5lff_k {
  fill: var(--svg-color--bfbfbf, #bfbfbf);
  d: path("M22 19.1c-.6.3-.5.5-1.1.5c-.4-.1-3.9-2.7-3.9-2.7q-.2-.8.4-1.5q.7-.8 1.4-.7s3.3 2.8 3.4 3.2c.2.6 0 .5-.1 1.2");
}

.xzjq9b1nl {
  stop-color: var(--svg-color--5596ea, #5596ea);
}

</style>
