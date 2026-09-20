<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><path fill="url(#tokenBrandedAero0)" class="tkkw6mvld"/><path class="t3ogf-8zx"/><path class="t_0xgy4lx"/><path class="h868dpbxy"/><defs><linearGradient id="tokenBrandedAero0" x1="18.281" x2="-2.338" y1="5.469" y2="29.15" gradientUnits="userSpaceOnUse"><stop class="ki0xeab2h"/><stop offset="1" class="m4bm9bb9y"/></linearGradient></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:aero" /></template>
<style>
.ft5dv1b6b {
  fill: none;
}

.h868dpbxy {
  fill: var(--svg-color--fff, #fff);
  d: path("m10.8 12.624l2.151-1.29l2.691 5.133l-.085.079z");
}

.ki0xeab2h {
  stop-color: var(--svg-color--1a1e21, #1A1E21);
}

.m4bm9bb9y {
  stop-color: var(--svg-color--06060a, #06060A);
}

.t_0xgy4lx {
  fill: var(--svg-color--fff, #fff);
  d: path("M6.193 14.049c1.249-2.619 2.51-5.243 3.758-7.873l.145-.018c.673 1.224 1.358 2.43 2.055 3.697a27.7 27.7 0 0 0-5.958 4.194m6.025 1.733c-.067.048-.128.121-.206.145c-1.473.606-2.952 1.17-4.528 1.394c-.424.06-.872.049-1.29-.03c-.716-.14-.982-.679-.68-1.346c.2-.412.467-.824.776-1.17c1.164-1.302 2.582-2.272 4.055-3.187a44.5 44.5 0 0 1 6.63-3.315c.158-.06.303-.14.485-.218l-.267-.485h1.71l.03.06l-1.073.473A37 37 0 0 0 9 13.388c-.455.376-.843.83-1.237 1.26c-.14.146-.248.334-.34.528c-.302.63-.048 1.14.643 1.2a7.6 7.6 0 0 0 1.818-.06c.788-.122 1.558-.346 2.334-.534");
}

.t3ogf-8zx {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 2.606a9.394 9.394 0 1 1 0 18.789a9.394 9.394 0 0 1 0-18.789M22 12a10 10 0 1 0-20 0a10 10 0 0 0 20 0");
}

.tkkw6mvld {
  d: path("M12 21.697a9.697 9.697 0 1 1 0-19.393a9.697 9.697 0 0 1 0 19.393");
}

</style>
