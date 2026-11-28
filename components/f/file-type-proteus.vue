<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<g transform="translate(-6.33 -35.26)scale(.90897)"><g class="k64rhpb9n"><path class="p_dolk0-p"/><path class="i__6ysi4t"/><path class="h6dqwdbrq"/></g><circle class="zajpzlb8r"/><g class="xojv4acyy"><circle class="gikalgc3u"/><circle class="bmx0l-biy"/><circle class="b68slcu_p"/><circle class="ylqbyr6xd"/></g><g class="mc-m9vhxf"><path class="sn0esxbcl"/><path class="rlvj6pbjs"/></g></g>`;
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

.gikalgc3u {
  cx: 16.18px;
  cy: 47.32px;
  r: 1.5px;
}

.h6dqwdbrq {
  d: path("M9.81 55.89c.12-2.3 6.69-4.15 14.74-4.15s14.62 1.85 14.74 4.15m-29.46.73c.12 2.3 6.69 4.15 14.74 4.15s14.63-1.85 14.74-4.15");
}

.i__6ysi4t {
  d: path("M32.78 65.71q.24-.04.39-.18c1.12-1.05-1.81-6.03-6.56-11.14c-4.74-5.1-9.5-8.39-10.62-7.35q-.12.1-.18.27");
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

.p_dolk0-p {
  d: path("M33.95 47.47a1 1 0 0 0-.18-.38c-1.04-1.13-6.03 1.81-11.13 6.55s-8.4 9.5-7.35 10.63q.1.11.27.17");
}

.rlvj6pbjs {
  d: path("M15.6 65.43c1.08 1.1 5.97-2 10.92-6.9s8.1-9.76 7.02-10.84");
}

.sn0esxbcl {
  d: path("M15.8 47.62c-1.13 1.05 2 5.73 6.74 10.83s9.12 8.3 10.25 7.25");
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
