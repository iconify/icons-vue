<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(-8.56 -40.39)"><g class="k64rhpb9n"><path class="v9jzzci2x"/><path class="sq-siubzx"/><path class="g6_6kcbsi"/></g><circle class="zajpzlb8r"/><g class="xojv4acyy"><circle class="gikalgc3u"/><circle class="bmx0l-biy"/><circle class="b68slcu_p"/><circle class="ylqbyr6xd"/></g><g class="mc-m9vhxf"><path class="o1i4gvbsq"/><path class="bw9mfackn"/></g></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-proteus" /></template>
<style>
.b68slcu_p {
  cx: 32.79px;
  cy: 65.47px;
  r: 1.5px;
}

.bmx0l-biy {
  cx: 15.74px;
  cy: 65.12px;
  r: 1.5px;
}

.bw9mfackn {
  d: path("M15.596 65.433c1.083 1.095 5.971-1.998 10.926-6.9c4.954-4.903 8.098-9.759 7.021-10.846");
}

.g6_6kcbsi {
  d: path("M9.81 55.89c.12-2.3 6.69-4.15 14.74-4.15c8.06 0 14.62 1.85 14.74 4.15m-29.46.73c.12 2.3 6.69 4.15 14.74 4.15c8.06 0 14.63-1.85 14.74-4.15");
}

.gikalgc3u {
  cx: 16.18px;
  cy: 47.32px;
  r: 1.5px;
}

.k64rhpb9n {
  fill: none;
  stroke: var(--svg-color--b3aaac, #b3aaac);
  stroke-linecap: square;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
}

.mc-m9vhxf {
  fill: none;
  stroke: var(--svg-color--b3aaac, #b3aaac);
  stroke-linecap: round;
  stroke-width: var(--svg-stroke-width--0-8px, 0.8px);
}

.o1i4gvbsq {
  d: path("M15.802 47.62c-1.128 1.048 1.99 5.726 6.735 10.832s9.12 8.302 10.249 7.253");
}

.sq-siubzx {
  d: path("M32.78 65.71q.24-.045.39-.18c1.12-1.05-1.81-6.03-6.56-11.14c-4.74-5.1-9.5-8.39-10.62-7.35q-.12.105-.18.27");
}

.v9jzzci2x {
  d: path("M33.95 47.47a.65.65 0 0 0-.18-.38c-1.04-1.13-6.03 1.81-11.13 6.55c-5.11 4.75-8.4 9.5-7.35 10.63c.07.08.16.13.27.17");
}

.xojv4acyy {
  fill: var(--svg-color--eee592, #eee592);
}

.ylqbyr6xd {
  cx: 33.44px;
  cy: 47.53px;
  r: 1.5px;
}

.zajpzlb8r {
  cx: 24.57px;
  cy: 56.56px;
  r: 6.5px;
  fill: var(--svg-color--2a5ea8, #2a5ea8);
}

</style>
