<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="fxatekbpr"/><path class="yn7ksmeol"/><path class="kze0mwblk"/><g class="fbp0m0b1e"><circle class="ry06sibgd"/><circle class="xrvu5hbnt"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:face-with-stuck-out-tongue" /></template>
<style>
.fbp0m0b1e {
  fill: var(--svg-color--664e27, #664e27);
}

.fxatekbpr {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M47.9 38H16.1c-.7 0-1.1.5-1.1 1c0 7.3 6 15 17 15s17-7.7 17-15c0-.5-.4-1-1.1-1");
}

.kze0mwblk {
  fill: var(--svg-color--e2596c, #e2596c);
  d: path("M33.5 44L32 57.8L30.5 44z");
}

.rhvdvboaq {
  cx: 32px;
  cy: 32px;
  r: 30px;
  fill: var(--svg-color--ffdd67, #ffdd67);
}

.ry06sibgd {
  cx: 20.5px;
  cy: 24.5px;
  r: 5px;
}

.xrvu5hbnt {
  cx: 43.5px;
  cy: 24.5px;
  r: 5px;
}

.yn7ksmeol {
  fill: var(--svg-color--ff717f, #ff717f);
  d: path("M41.2 44H22.8c-.7 0-.8.3-.8.8v4C22 57.6 26.5 62 32 62s10-4.4 10-13.2v-4c0-.5-.1-.8-.8-.8");
}

</style>
