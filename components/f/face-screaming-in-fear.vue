<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><linearGradient id="SVG87NodcIz" x1="64.1" x2="64.1" y1="119.73" y2="6.64" gradientUnits="userSpaceOnUse"><stop offset=".16" class="m_j2at8le"/><stop offset=".33" class="pilgl2bji"/><stop offset=".81" class="hqtov9bwy"/></linearGradient><linearGradient id="SVGA0Cpte8f" x1="64.1" x2="64.1" y1="87.37" y2="5.65" gradientUnits="userSpaceOnUse"><stop offset=".19" class="lfxua2bme"/><stop offset=".28" class="lg5e88bpc"/><stop offset=".4" class="gnr799bmj"/><stop offset=".52" class="pxbo_nygy"/><stop offset=".64" class="exkhulb-a"/><stop offset=".74" class="q7ehuqgkq"/><stop offset=".83" class="jpzq5tb3j"/><stop offset=".89" class="zvhoujbdx"/></linearGradient><linearGradient id="SVGJ7pGweVY" x1="64.1" x2="64.1" y1="124.71" y2="83.57" gradientUnits="userSpaceOnUse"><stop offset="0" class="y0ijp83cb"/><stop offset=".15" class="dlltevv8z"/><stop offset=".47" class="cagt8m_0v"/><stop offset=".62" class="m-0me6bst"/></linearGradient><linearGradient id="SVGgWHuHdYM" x1="88.07" x2="115.59" y1="91.28" y2="104.36" gradientUnits="userSpaceOnUse"><stop offset="0" class="md120d8ra"/><stop offset="1" class="ah0nj420a"/></linearGradient><linearGradient id="SVG4AZVhepq" x1="903.75" x2="931.26" y1="91.28" y2="104.36" gradientTransform="matrix(-1 0 0 1 943.68 0)" href="#SVGgWHuHdYM"/><radialGradient id="SVG0VfhacUl" cx="64.1" cy="62.81" r="57.11" fx="64.1" fy="62.81" gradientUnits="userSpaceOnUse"><stop offset=".5" class="r_-r4-l8z"/><stop offset=".92" class="pilgl2bji"/><stop offset="1" class="m_j2at8le"/></radialGradient></defs><path fill="url(#SVG0VfhacUl)" class="db4q8bbmm"/><path fill="url(#SVG87NodcIz)" class="db4q8bbmm"/><path fill="url(#SVGA0Cpte8f)" class="db4q8bbmm"/><path fill="url(#SVGJ7pGweVY)" class="y4b7n1cou"/><path class="db2bn3bsc"/><path fill="url(#SVGgWHuHdYM)" class="sc_7jn89a"/><g class="nxakybc5z"><path class="xrx2lpp-b"/><path class="kuoodlb6n"/></g><path class="hqfkcbcgt"/><path fill="url(#SVG4AZVhepq)" class="oqj211b5y"/><g class="nxakybc5z"><path class="u5e8r9i5f"/><path class="aa3q34b4a"/></g><path class="u3838ubow"/><path class="mpdkwab0k"/><path class="hf4v8fjfc"/><path class="akk467nia"/><path class="rz834dopo"/><path class="lzzf13e4h"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:face-screaming-in-fear" /></template>
<style>
.aa3q34b4a {
  d: path("M39.66 123.78c-3.24 0-5.3-.65-7.59-1.79c0 0 3.7 1.02 7.56.35s7.47-3.66 7.69-9.98c.3-8.77-4.2-14.66-6.89-18.19c-.32-.42-.61-.8-.87-1.16c-.95-1.29-2.05-3.13-3.21-5.09c-2.12-3.55-4.33-7.39-6.55-9.37c-2.49-2.22-4.38-.88-4.79-.17c-.64 1.09-.34 1.95.74 3.07c.88.91 5.04 5.4 6.77 13.41c0 0 .34 1.26-.42 1.41c-.65.14-.92-1-.92-1c-2.01-7.27-6.82-12.23-7.27-12.79c-1.92-2.36-2.1-4.11-.89-5.91c.83-1.23 2.6-2.14 4.01-2.31c1.67-.21 3.41.24 5.2 1.89c2.49 2.3 4.84 6.21 7.06 9.93c1.13 1.9 2.2 3.69 3.07 4.87c.25.34.54.72.84 1.12c2.91 3.82 7.43 10.2 7.46 19.97c.02 7.15-4.23 11.73-10.97 11.73Z");
}

.ah0nj420a {
  stop-color: var(--svg-color--ffc400, #ffc400);
}

.akk467nia {
  fill: var(--svg-color--fff, #fff);
  d: path("M84.28 37.41c4.52 0 9.28 2.83 12.45 8.86c4.62 8.76 2.21 17.31-3.48 20.91a10.8 10.8 0 0 1-5.82 1.71c-4.51 0-9.28-2.83-12.45-8.86c-4.62-8.76-2.21-17.31 3.48-20.91c1.78-1.13 3.77-1.71 5.82-1.71");
}

.cagt8m_0v {
  stop-color: var(--svg-color--rgba-209-117-25-25, rgba(209, 117, 25, .25));
  stop-opacity: 0.25;
}

.db2bn3bsc {
  fill: var(--svg-color--d17519, #d17519);
  d: path("M108.24 21.54c6.01 7.13 9.81 16.3 9.81 27.65c0 14.52-2.3 20.22-14.29 34.01c-7.56 8.69-9.63 14.2-12.43 18.97c-4.11 6.99-8.46.2-10.87 6.68c-2.93 7.86-12 9.85-16.85 9.85s-13.86-2.98-15.56-9.17c-1.21-4.4-5.49 4.22-8.56 1.1c5.72 6.89 12.84 10.26 24.49 10.29c14.84-.04 22.59-5.46 29.2-16.71c2.8-4.76 4.87-10.28 12.43-18.97c11.99-13.79 14.29-19.49 14.29-34.01c0-12.48-4.59-22.31-11.65-29.7Z");
}

.db4q8bbmm {
  d: path("M63.97 4.22C38.83 4.22 8.31 18.9 8.31 51.25c0 14.52 2.3 20.22 14.29 34.01c7.56 8.69 9.63 14.2 12.43 18.97c6.62 11.25 14.1 16.67 28.94 16.71c14.84-.04 22.59-5.46 29.2-16.71c2.8-4.76 4.87-10.28 12.43-18.97c11.99-13.79 14.29-19.49 14.29-34.01c0-32.35-30.78-47.03-55.92-47.03");
}

.dlltevv8z {
  stop-color: var(--svg-color--rgba-209-117-25-79, rgba(209, 117, 25, .79));
  stop-opacity: 0.79;
}

.exkhulb-a {
  stop-color: var(--svg-color--rgba-88-136-250-79, rgba(88, 136, 250, .79));
  stop-opacity: 0.79;
}

.gnr799bmj {
  stop-color: var(--svg-color--rgba-77-161-241-43, rgba(77, 161, 241, .43));
  stop-opacity: 0.43;
}

.hf4v8fjfc {
  fill: var(--svg-color--d17519, #d17519);
  d: path("M39.91 70.86c-5.5 0-13.03-4.16-13.03-14.51c0-6.94 2.61-11.32 5.8-14.43c3.89-3.79 7.86-4.52 9.67-4.52c.38 0 .34.1 0 .16c-4.08.69-12.1 7.25-12.1 18.2c0 8.33 6.19 11.43 9.62 11.43s9.71-.81 14.59-10.49c0 0-.26 3.73-4 8.67c-2.44 3.22-6.49 5.5-10.54 5.5Z");
}

.hqfkcbcgt {
  fill: var(--svg-color--d17519, #d17519);
  d: path("M106.98 98.2c5.3-10.67 8.09-13.75 10.59-16.92c2.33-2.95 3.27-5.2 2.2-7.47c-.9-1.91-2.91-3.49-5.14-3.51c-2.63-.02-4.82 1.89-4.82 1.89l2.28 2.02c.49-.4 3.54-1.85 4.91.16c1.2 1.77.43 3.54-1.3 5.5c-3.54 4.01-7.03 10.08-9.95 17.88c-.31.83-.5 2.16-.17 2.26s.87-.75 1.4-1.81");
}

.hqtov9bwy {
  stop-color: var(--svg-color--fde030, #fde030);
  stop-opacity: 0;
}

.jpzq5tb3j {
  stop-color: var(--svg-color--rgba-94-123-254-98, rgba(94, 123, 254, .98));
  stop-opacity: 0.98;
}

.kuoodlb6n {
  d: path("M88.34 123.78c3.24 0 5.3-.65 7.59-1.79c0 0-3.7 1.02-7.56.35s-7.47-3.66-7.69-9.98c-.3-8.77 4.2-14.66 6.89-18.19c.32-.42.61-.8.87-1.16c.95-1.29 2.05-3.13 3.21-5.09c2.12-3.55 4.33-7.39 6.55-9.37c2.49-2.22 4.38-.88 4.79-.17c.64 1.09.34 1.95-.74 3.07c-.88.91-5.04 5.4-6.77 13.41c0 0-.34 1.26.42 1.41c.65.14.92-1 .92-1c2.01-7.27 6.82-12.23 7.27-12.79c1.92-2.36 2.1-4.11.89-5.91c-.83-1.23-2.6-2.14-4.01-2.31c-1.67-.21-3.41.24-5.2 1.89c-2.49 2.3-4.84 6.21-7.06 9.93c-1.13 1.9-2.2 3.69-3.07 4.87c-.25.34-.54.72-.84 1.12c-2.91 3.82-7.43 10.2-7.46 19.97c-.02 7.15 4.23 11.73 10.97 11.73Z");
}

.lfxua2bme {
  stop-color: var(--svg-color--40c0e7, #40c0e7);
  stop-opacity: 0;
}

.lg5e88bpc {
  stop-color: var(--svg-color--rgba-69-178-235-19, rgba(69, 178, 235, .19));
  stop-opacity: 0.19;
}

.lzzf13e4h {
  fill: var(--svg-color--422b0d, #422b0d);
  d: path("M77.82 82.89c-1.12-7.6-6.22-13.3-13.82-13.3s-12.71 5.71-13.82 13.3c-.61 4.14-.62 11.68 1.38 17.47S56.4 111.54 64 111.54s10.45-5.38 12.44-11.18c2-5.79 1.99-13.33 1.38-17.47");
}

.m_j2at8le {
  stop-color: var(--svg-color--f4a223, #f4a223);
}

.m-0me6bst {
  stop-color: var(--svg-color--d17519, #d17519);
  stop-opacity: 0;
}

.md120d8ra {
  stop-color: var(--svg-color--fff176, #fff176);
}

.mpdkwab0k {
  fill: var(--svg-color--fff, #fff);
  d: path("M43.72 37.41c2.05 0 4.04.58 5.82 1.71c5.7 3.61 8.1 12.16 3.48 20.91c-3.17 6.03-7.94 8.86-12.45 8.86c-2.05 0-4.04-.58-5.82-1.71c-5.7-3.61-8.1-12.16-3.48-20.91c3.17-6.03 7.93-8.86 12.45-8.86");
}

.nxakybc5z {
  fill: var(--svg-color--d17519, #d17519);
  stroke-width: var(--svg-stroke-width--0px, 0px);
}

.oqj211b5y {
  d: path("M24.81 77c-.68-.84-2.06-2.54-2.97-3.16c-1.83-1.25-3.34-2.74-4.78-1.31l-1.35 1.32s-4.2-3.3-6.52.32c-1.48 2.3.68 5.65 2.39 7.87c1.63 2.11 7.77 11.51 9.27 14.96c4.76 10.99 3.55 13.38 6.5 19.68c1.89 4.02 4.59 6.28 9.77 6.46c7.59.26 12.39-4.45 12.33-10.02c-.08-7.02-3.51-15.59-8.03-19.93c-5.65-5.44-8.13-12.55-10.05-15.04c-1.33-1.72-4.28-1.58-5.46-1.43s-1.1.28-1.1.28");
}

.pilgl2bji {
  stop-color: var(--svg-color--f7c02b, #f7c02b);
}

.pxbo_nygy {
  stop-color: var(--svg-color--rgba-83-147-246-63, rgba(83, 147, 246, .63));
  stop-opacity: 0.63;
}

.q7ehuqgkq {
  stop-color: var(--svg-color--rgba-92-128-252-91, rgba(92, 128, 252, .91));
  stop-opacity: 0.91;
}

.r_-r4-l8z {
  stop-color: var(--svg-color--fde030, #fde030);
}

.rz834dopo {
  fill: var(--svg-color--d17519, #d17519);
  d: path("M88.09 70.86c5.5 0 13.03-4.16 13.03-14.51c0-6.94-2.61-11.32-5.8-14.43c-3.89-3.79-7.86-4.52-9.67-4.52c-.38 0-.34.1 0 .16c4.08.69 12.1 7.25 12.1 18.2c0 8.33-6.19 11.43-9.62 11.43s-9.71-.81-14.59-10.49c0 0 .26 3.73 4 8.67c2.44 3.22 6.49 5.5 10.54 5.5Z");
}

.sc_7jn89a {
  d: path("M103.19 77c.68-.84 2.06-2.54 2.97-3.16c1.83-1.25 3.34-2.74 4.78-1.31l1.35 1.32s4.2-3.3 6.52.32c1.48 2.3-.68 5.65-2.39 7.87c-1.63 2.11-7.77 11.51-9.27 14.96c-4.76 10.99-3.55 13.38-6.5 19.68c-1.89 4.02-4.59 6.28-9.77 6.46c-7.59.26-12.39-4.45-12.33-10.02c.08-7.02 3.51-15.59 8.03-19.93c5.65-5.44 8.13-12.55 10.05-15.04c1.33-1.72 4.28-1.58 5.46-1.43s1.1.28 1.1.28");
}

.u3838ubow {
  fill: var(--svg-color--d17519, #d17519);
  d: path("M21.02 98.2c-5.3-10.67-8.09-13.75-10.59-16.92c-2.33-2.95-3.27-5.2-2.2-7.47c.9-1.91 2.91-3.49 5.14-3.51c2.63-.02 4.82 1.89 4.82 1.89l-2.28 2.02c-.49-.4-3.54-1.85-4.91.16c-1.2 1.77-.43 3.54 1.3 5.5c3.54 4.01 7.03 10.08 9.95 17.88c.31.83.5 2.16.17 2.26s-.87-.75-1.4-1.81");
}

.u5e8r9i5f {
  d: path("M25.45 96.39c-3.35-8.88-8.79-14.24-10.54-16.6l-.33-.45c-1.7-2.33-1.29-4.26-.64-5.46c.59-1.12 2.58-2.87 4.8-3c1.88-.12 4.76.65 7.72 4.92l-2.47 1.77c-1.74-2.5-3.49-3.87-5.12-3.78c-1.07.06-2.24.98-2.47 1.39c-.43.78-.54 1.64.37 2.88l.32.43c1.82 2.45 7.52 10.14 9.75 17.52c.23.76.36 1.68-.3 1.79s-.87-.85-1.08-1.42Z");
}

.xrx2lpp-b {
  d: path("M102.55 96.39c3.35-8.88 8.79-14.24 10.54-16.6l.33-.45c1.7-2.33 1.29-4.26.64-5.46c-.59-1.12-2.58-2.87-4.8-3c-1.88-.12-4.76.65-7.72 4.92l2.47 1.77c1.74-2.5 3.49-3.87 5.12-3.78c1.07.06 2.24.98 2.47 1.39c.43.78.54 1.64-.37 2.88l-.32.43c-1.82 2.45-7.52 10.14-9.75 17.52c-.23.76-.36 1.68.3 1.79s.87-.85 1.08-1.42Z");
}

.y0ijp83cb {
  stop-color: var(--svg-color--d17519, #d17519);
}

.y4b7n1cou {
  d: path("M8.31 51.25c0 14.52 2.3 20.22 14.29 34.01c7.56 8.69 9.63 14.2 12.43 18.97c6.62 11.25 14.1 16.67 28.94 16.71c14.84-.04 22.59-5.46 29.2-16.71c2.8-4.76 4.87-10.28 12.43-18.97c11.99-13.79 14.29-19.49 14.29-34.01z");
}

.zvhoujbdx {
  stop-color: var(--svg-color--5f7aff, #5f7aff);
}

</style>
