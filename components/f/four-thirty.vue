<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<defs><path id="SVGZeETcFtq" class="cavir2b0b"/><path id="SVGhBAbgbcy" class="kdfks_bus"/></defs><use href="#SVGZeETcFtq" class="n1mjunbsu"/><path class="ookrwvbdr"/><path class="u30fqcczo"/><circle class="lv8p82s9b"/><path class="y4gpgm1lu"/><g class="ehej3-bmx"><use href="#SVGhBAbgbcy"/><use href="#SVGhBAbgbcy"/></g><path class="j5m68bcku"/><path class="dj5ptob4a"/><path class="g318r_btr"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto-v1:four-thirty" /></template>
<style>
.cavir2b0b {
  d: path("M64 6.27C32.17 6.27 6.27 32.16 6.27 64s25.9 57.73 57.74 57.73c31.83 0 57.73-25.89 57.73-57.73C121.73 32.16 95.84 6.27 64 6.27");
}

.dj5ptob4a {
  fill: var(--svg-color--fff, #fff);
  d: path("M67.69 64c0 2.04-1.65 3.69-3.69 3.69s-3.69-1.65-3.69-3.69c0-2.03 1.65-3.68 3.69-3.68s3.69 1.65 3.69 3.68");
}

.ehej3-bmx {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.g318r_btr {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M64 10.38c-2.04 0-3.68 1.65-3.68 3.68A3.67 3.67 0 0 0 64 17.74c2.04 0 3.69-1.65 3.69-3.68A3.7 3.7 0 0 0 64 10.38");
}

.j5m68bcku {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("m58.338 64.841l6.513-6.512L90.81 84.29l-6.513 6.513z");
}

.kdfks_bus {
  d: path("M73.79 63.99c0 5.41-4.38 9.79-9.78 9.79s-9.78-4.38-9.78-9.79c0-5.4 4.37-9.77 9.78-9.77c5.39 0 9.78 4.37 9.78 9.77");
}

.lv8p82s9b {
  cx: 14.07px;
  cy: 64px;
  r: 3.68px;
  fill: var(--svg-color--2f2f2f, #2f2f2f);
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.ookrwvbdr {
  fill: var(--svg-color--40c0e7, #40c0e7);
  d: path("M64 127.9C28.77 127.9.1 99.23.1 64S28.77.1 64 .1s63.89 28.67 63.89 63.9S99.23 127.9 64 127.9M64 6.27C32.17 6.27 6.27 32.16 6.27 64s25.9 57.73 57.74 57.73c31.83 0 57.73-25.89 57.73-57.73C121.73 32.16 95.84 6.27 64 6.27");
}

.u30fqcczo {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M117.62 64a3.685 3.685 0 1 1-7.37.01a3.685 3.685 0 0 1 7.37-.01m-7.19-26.81c1.01 1.77.41 4.02-1.35 5.03a3.67 3.67 0 0 1-5.03-1.35a3.673 3.673 0 0 1 1.35-5.03c1.76-1.01 4.02-.41 5.03 1.35M90.81 17.56a3.694 3.694 0 0 1 1.35 5.04a3.69 3.69 0 0 1-5.03 1.35a3.69 3.69 0 0 1-1.35-5.04c1.01-1.76 3.27-2.36 5.03-1.35m-53.62 0a3.69 3.69 0 0 1 5.03 1.35c1.02 1.77.42 4.01-1.34 5.03a3.67 3.67 0 0 1-5.03-1.35a3.68 3.68 0 0 1 1.34-5.03M17.57 37.19a3.673 3.673 0 0 1 5.03-1.35a3.69 3.69 0 0 1 1.35 5.03a3.69 3.69 0 0 1-5.04 1.35a3.68 3.68 0 0 1-1.34-5.03");
}

.y4gpgm1lu {
  fill: var(--svg-color--2f2f2f, #2f2f2f);
  d: path("M17.56 90.81a3.69 3.69 0 0 1 1.35-5.03a3.685 3.685 0 0 1 5.04 1.35a3.68 3.68 0 0 1-1.35 5.03a3.703 3.703 0 0 1-5.04-1.35m19.63 19.62a3.69 3.69 0 0 1-1.35-5.03a3.683 3.683 0 0 1 5.04-1.35a3.68 3.68 0 0 1 1.35 5.03c-1.02 1.76-3.28 2.38-5.04 1.35m53.62 0c-1.76 1.01-4.02.41-5.03-1.35a3.67 3.67 0 0 1 1.35-5.03a3.67 3.67 0 0 1 5.03 1.35c1.01 1.76.41 4.02-1.35 5.03m19.62-19.62a3.68 3.68 0 0 1-5.03 1.35a3.673 3.673 0 0 1-1.35-5.03c1.01-1.76 3.27-2.36 5.03-1.35a3.67 3.67 0 0 1 1.35 5.03M59.4 60.61h9.21v56.05H59.4z");
}

</style>
