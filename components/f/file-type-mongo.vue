<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGmsjVGeRs" x1="-645.732" x2="-654.59" y1="839.188" y2="839.25" gradientTransform="matrix(-.977 -.323 -.29 .877 -375.944 -928.287)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="q0z6hdcxd"/><stop offset=".563" class="af7y40hhz"/><stop offset=".683" class="qj9hb51eq"/><stop offset=".768" class="ww4rnx14k"/><stop offset=".837" class="xlm0j495h"/><stop offset=".896" class="o_pt3q22q"/><stop offset=".948" class="tvwrn0bse"/><stop offset=".994" class="u-f0t0cfy"/><stop offset="1" class="gg2u05m6f"/></linearGradient><linearGradient id="SVGajUg6c6y" x1="-644.287" x2="-657.028" y1="823.405" y2="845.476" gradientTransform="matrix(-.977 -.323 -.29 .877 -375.944 -928.287)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vdbljq88h"/><stop offset="1" class="e9v4b1bni"/></linearGradient><linearGradient id="SVGnjaRbbDk" x1="-643.386" x2="-652.418" y1="839.485" y2="833.417" gradientTransform="matrix(-.977 -.323 -.29 .877 -375.944 -928.287)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x3bbku2do"/><stop offset=".352" class="dqc71bbtr"/><stop offset=".956" class="pa9q6cb8z"/><stop offset="1" class="vdzv01mbh"/></linearGradient></defs><path fill="url(#SVGmsjVGeRs)" class="w9i9pkb5s"/><path fill="url(#SVGajUg6c6y)" class="tnv5_ebzv"/><path fill="url(#SVGnjaRbbDk)" class="ohb10jbdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:file-type-mongo" /></template>
<style>
.af7y40hhz {
  stop-color: var(--svg-color--9b9977, #9b9977);
}

.dqc71bbtr {
  stop-color: var(--svg-color--4ba74b, #4ba74b);
}

.e9v4b1bni {
  stop-color: var(--svg-color--3f9143, #3f9143);
}

.gg2u05m6f {
  stop-color: var(--svg-color--fbf9ef, #fbf9ef);
}

.o_pt3q22q {
  stop-color: var(--svg-color--c9c7b0, #c9c7b0);
}

.ohb10jbdv {
  d: path("M15.487 26.569S9.366 22.4 9.72 15.025a15.54 15.54 0 0 1 5.519-11.648A1.73 1.73 0 0 0 15.846 2c.381.82.319 12.243.359 13.579c.155 5.197-.289 10.009-.718 10.99");
}

.pa9q6cb8z {
  stop-color: var(--svg-color--67b554, #67b554);
}

.q0z6hdcxd {
  stop-color: var(--svg-color--999875, #999875);
}

.qj9hb51eq {
  stop-color: var(--svg-color--a09f7e, #a09f7e);
}

.tnv5_ebzv {
  d: path("M17.026 26.329a13.22 13.22 0 0 0 5-13.225c-1.47-6.485-4.951-8.617-5.326-9.431a10 10 0 0 1-.825-1.6l.277 18.069s-.574 5.522.874 6.187");
}

.tvwrn0bse {
  stop-color: var(--svg-color--deddcb, #deddcb);
}

.u-f0t0cfy {
  stop-color: var(--svg-color--f8f6eb, #f8f6eb);
}

.vdbljq88h {
  stop-color: var(--svg-color--48a547, #48a547);
}

.vdzv01mbh {
  stop-color: var(--svg-color--69b655, #69b655);
}

.w9i9pkb5s {
  d: path("m16.62 30l-.751-.249s.1-3.8-1.275-4.067c-.9-1.048.133-44.741 3.423-.149a2.7 2.7 0 0 0-1.333 1.523A14 14 0 0 0 16.62 30");
}

.ww4rnx14k {
  stop-color: var(--svg-color--a9a889, #a9a889);
}

.x3bbku2do {
  stop-color: var(--svg-color--41a247, #41a247);
}

.xlm0j495h {
  stop-color: var(--svg-color--b7b69a, #b7b69a);
}

</style>
