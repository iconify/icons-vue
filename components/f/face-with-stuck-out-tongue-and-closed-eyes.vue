<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<circle class="rhvdvboaq"/><path class="fxatekbpr"/><path class="yn7ksmeol"/><path class="kze0mwblk"/><path class="ftkxw2g3e"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:face-with-stuck-out-tongue-and-closed-eyes" /></template>
<style>
.ftkxw2g3e {
  fill: var(--svg-color--664e27, #664e27);
  d: path("M51.7 23.4c.6.3.3 1-.2 1.1c-2.7.4-5.5.9-8.3 2.4c4 .7 7.2 2.7 9 4.8c.4.5-.1 1.1-.5 1c-4.8-1.7-9.7-2.7-15.8-2c-.5 0-.9-.2-.8-.7c1.6-7.3 10.9-10 16.6-6.6m-39.4 0c-.6.3-.3 1 .2 1.1c2.7.4 5.5.9 8.3 2.4c-4 .7-7.2 2.7-9 4.8c-.4.5.1 1.1.5 1c4.8-1.7 9.7-2.7 15.8-2c.5 0 .9-.2.8-.7c-1.6-7.3-10.9-10-16.6-6.6");
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

.yn7ksmeol {
  fill: var(--svg-color--ff717f, #ff717f);
  d: path("M41.2 44H22.8c-.7 0-.8.3-.8.8v4C22 57.6 26.5 62 32 62s10-4.4 10-13.2v-4c0-.5-.1-.8-.8-.8");
}

</style>
