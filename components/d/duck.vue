<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":128,"height":128};
const content = `<linearGradient id="SVGdJ9uMe1Z" x1="47.489" x2="51.02" y1="11.504" y2="45.102" gradientUnits="userSpaceOnUse"><stop offset=".171" class="zyjkjzy_a"/><stop offset=".345" class="lc4fekb5q"/><stop offset=".671" class="tpsriaczu"/><stop offset="1" class="eiajoju3f"/></linearGradient><path fill="url(#SVGdJ9uMe1Z)" class="d6husvbah"/><path class="qmepribdt"/><path class="lws858brt"/><path class="l5pmdpmlz"/><path class="pxtyxmbya"/><path class="zq66-jbzp"/><path class="mxxr1g07l"/><path class="p3jouhtkb"/><path class="ju5c6q_ve"/><path class="nq50blkiw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="noto:duck" /></template>
<style>
.d6husvbah {
  d: path("M35.84 48.65s5.84-8.38 5.42-11.61c-.42-3.24-1.55-3.94-4.79-5.07s-5.14-2.89-5.14-2.89s-2.35-11.03-2.11-12.39c.28-1.62 6.12-12.53 19.99-12.53c13.37 0 18.86 11.22 18.16 19.85c-.63 7.81-3.52 10-5.56 16.47c-2.04 6.48-3.03 10.35-3.03 10.35l-12.04 2.46l-10.07-2.18z");
}

.eiajoju3f {
  stop-color: var(--svg-color--2f502a, #2f502a);
}

.ju5c6q_ve {
  fill: var(--svg-color--84574e, #84574e);
  d: path("M26.03 69.11C25.28 89.56 40.7 99.28 65.17 99.7c27.12.47 37.61-15.44 39.23-25.43c1.69-10.45-5.07-12.67-5.07-12.67s6.76-2.82 3.73-9.5c-1.41-.28-8.35 1.57-21.54.21c-13.1-1.35-22.08.94-22.08.94s-3.28 3.57-12.67 3.1c-11.25-.56-13.42-4.97-13.42-4.97s-6.85 5.01-7.32 17.73");
}

.l5pmdpmlz {
  fill: var(--svg-color--b0b0b1, #b0b0b1);
  d: path("M85.67 55.69c2.35-.28 12.66-3.54 16.33-2.6c4.43 1.13 8.85 4.25 7.95 14.15c-1.16 12.85-10.29 20.68-14.22 22.83C88.7 93.91 81.94 94 81.94 94s1.39-38.03 3.73-38.31");
}

.lc4fekb5q {
  stop-color: var(--svg-color--089e42, #089e42);
}

.lws858brt {
  fill: var(--svg-color--5e6367, #5e6367);
  d: path("M98.66 54.49s4.8-.94 4.82-4.2c.01-3.26-1.74-1.84-1.76-4.21s4.24-2.93 7.04-.94c2.21 1.57 7.26 6.68 6.98 17.29c-.38 14.41-7.92 24.95-19.79 31.47c-9.68 5.31-23.96 4.68-23.96 4.68z");
}

.mxxr1g07l {
  fill: var(--svg-color--73df86, #73df86);
  d: path("M50.92 25.57c2.47-.78 4.3-.79 4.04-2.47c-.3-1.93-3.51-1.38-5.55-.3c-2.17 1.15-4.99 3.11-3.74 4.7c1.33 1.69 3.83-1.48 5.25-1.93");
}

.nq50blkiw {
  fill: var(--svg-color--b79277, #b79277);
  d: path("M52.03 73.14c2.28 7.9 10.42 12.67 22.52 12.11c10.98-.51 18.96-8.17 20.27-14.92c1.43-7.34-1.55-10.14-1.55-10.14s6.34-2.3 6.34-6.76c-3.57-2.16-14.92-3.66-27.5-4.13c-8.16-.3-12.76 2.72-12.76 2.72S47.8 58.5 52.03 73.14");
}

.p3jouhtkb {
  fill: var(--svg-color--fff, #fff);
  d: path("M33.16 51.6s2.16 9.43 12.95 7.84c7.71-1.14 13.42-4.97 13.42-4.97l.09-6.29s-5.12 3-11.26 2.91c-6.38-.09-11.92-3.38-11.92-3.38z");
}

.pxtyxmbya {
  fill: var(--svg-color--ffbf18, #ffbf18);
  d: path("M7.12 25.07c0 1.2 7.46 4.72 14.5 5.56s11.4-.28 11.4-.28s-1.2-3.03-1.2-5.28s1.16-7.9-.63-9.22c-1.62-1.2-2.96 1.27-3.94 1.97c-.99.7-3.8 2.67-8.17 2.82s-8.17-.56-9.71.28s-2.25 2.88-2.25 4.15");
}

.qmepribdt {
  fill: var(--svg-color--ff5d10, #ff5d10);
  d: path("M53.25 96.51s.75 7.64-.02 8.57c-.78.93-12.44 3.63-13.76 4.62c-1.43 1.07-.82 3.47 2.22 6.24s5.59 3.25 7.34 2.53c2.06-.84 5.63-3.57 7.23-4.79c1.28-.98 3.2-3.06 3.46-4.73c.27-1.67-.56-11.48-.56-11.48zm15.2 2.68s1.1 8.92.56 10c-1.41 2.82-9.47 9.16-10 11.26c-.42 1.69 3.8 5.07 8.02 5.16c5.64.13 9.17-2.1 9.57-3.33c.56-1.74-1.55-11.97-1.83-12.53s.14-15.06.14-15.06z");
}

.tpsriaczu {
  stop-color: var(--svg-color--1a7a37, #1a7a37);
}

.zq66-jbzp {
  fill: var(--svg-color--2d2b33, #2d2b33);
  d: path("M50.2 20.77c-.42 1.75-1.61 3.12-3.94 2.75c-2.18-.35-3.24-2.6-2.6-4.79c.5-1.73 1.79-2.9 3.97-2.53c2.5.42 2.97 2.88 2.57 4.57");
}

.zyjkjzy_a {
  stop-color: var(--svg-color--01ab46, #01ab46);
}

</style>
