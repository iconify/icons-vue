<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGFKntFdWC" x1="-659.847" x2="-666.491" y1="839.557" y2="839.603" gradientTransform="matrix(-.977 -.323 -.29 .877 -378.211 -928.733)" gradientUnits="userSpaceOnUse"><stop offset=".231" class="q0z6hdcxd"/><stop offset=".563" class="af7y40hhz"/><stop offset=".683" class="qj9hb51eq"/><stop offset=".768" class="ww4rnx14k"/><stop offset=".837" class="xlm0j495h"/><stop offset=".896" class="o_pt3q22q"/><stop offset=".948" class="tvwrn0bse"/><stop offset=".994" class="u-f0t0cfy"/><stop offset="1" class="gg2u05m6f"/></linearGradient><linearGradient id="SVGO6j3qbmz" x1="-658.764" x2="-668.32" y1="827.72" y2="844.273" gradientTransform="matrix(-.977 -.323 -.29 .877 -378.211 -928.733)" gradientUnits="userSpaceOnUse"><stop offset="0" class="vdbljq88h"/><stop offset="1" class="e9v4b1bni"/></linearGradient><linearGradient id="SVGhdGLnc9G" x1="-658.088" x2="-664.862" y1="839.78" y2="835.229" gradientTransform="matrix(-.977 -.323 -.29 .877 -378.211 -928.733)" gradientUnits="userSpaceOnUse"><stop offset="0" class="x3bbku2do"/><stop offset=".352" class="dqc71bbtr"/><stop offset=".956" class="pa9q6cb8z"/><stop offset="1" class="vdzv01mbh"/></linearGradient></defs><path class="pm5-hxbjk"/><path fill="url(#SVGFKntFdWC)" class="m952sgbpe"/><path fill="url(#SVGO6j3qbmz)" class="um0b65bym"/><path fill="url(#SVGhdGLnc9G)" class="wspr2obdv"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-mongodb-opened" /></template>
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

.m952sgbpe {
  d: path("m26.775 31l-.563-.187s.072-2.851-.956-3.05c-.678-.786.1-33.556 2.567-.112a2.03 2.03 0 0 0-1 1.142A10.6 10.6 0 0 0 26.775 31");
}

.o_pt3q22q {
  stop-color: var(--svg-color--c9c7b0, #c9c7b0);
}

.pa9q6cb8z {
  stop-color: var(--svg-color--67b554, #67b554);
}

.pm5-hxbjk {
  fill: var(--svg-color--78c47c, #78c47c);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v16.8h25.2v-21Zm0 18.7H6.6V11.8h20.8Zm0-14.5h-8.2l1-2.1h7.1v2.1Zm-1.7 4H.5l3.8 12.8h25.2Z");
}

.q0z6hdcxd {
  stop-color: var(--svg-color--999875, #999875);
}

.qj9hb51eq {
  stop-color: var(--svg-color--a09f7e, #a09f7e);
}

.tvwrn0bse {
  stop-color: var(--svg-color--deddcb, #deddcb);
}

.u-f0t0cfy {
  stop-color: var(--svg-color--f8f6eb, #f8f6eb);
}

.um0b65bym {
  d: path("M27.079 28.247a9.92 9.92 0 0 0 3.748-9.919c-1.1-4.864-3.711-6.463-3.992-7.073a7.3 7.3 0 0 1-.619-1.2l.208 13.552s-.431 4.141.655 4.64");
}

.vdbljq88h {
  stop-color: var(--svg-color--48a547, #48a547);
}

.vdzv01mbh {
  stop-color: var(--svg-color--69b655, #69b655);
}

.wspr2obdv {
  d: path("M25.925 28.427S21.334 25.3 21.6 19.769a11.66 11.66 0 0 1 4.139-8.736A1.3 1.3 0 0 0 26.194 10c.286.615.239 9.182.269 10.184c.117 3.898-.216 7.507-.538 8.243");
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
