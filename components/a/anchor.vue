<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<g class="s7u4i-btv"><path class="rp6uw8keb"/><path class="h1l6k3-kj"/></g><path class="yqdljvgzf"/><path class="h00tkfr3i"/><path class="eic1a1b9y"/><path class="cgtp4ic9o"/><path class="w4ndvlyfw"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:anchor" /></template>
<style>
.cgtp4ic9o {
  fill: var(--svg-color--b2c1c0, #b2c1c0);
  d: path("M41 22c-5.9 1.4-12.1 1.4-18 0v-3.9c5.9-1.4 12.1-1.4 18 0z");
}

.eic1a1b9y {
  fill: var(--svg-color--62727a, #62727a);
  d: path("M27 12.5c.2-.2 2 2.1 5 2c2.9.1 4.8-2.2 5-2c.3.1-1.4 3-5 3s-5.3-2.9-5-3M41.3 50c-3.3 0-7.3-2.5-7.4-14.6c0-3-.2-9.4-.3-14.4H32v39.9c1.4-.8 5.9-3.4 10.5-6.4c9.7-6.5 13.4-12.2 14.7-15.7C50.5 46.3 45.3 50 41.3 50");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.h00tkfr3i {
  fill: var(--svg-color--b2c1c0, #b2c1c0);
  d: path("M32 2c-3.9 0-7 3.1-7 7s3.1 7 7 7s7-3.1 7-7s-3.1-7-7-7m0 11c-2.2 0-4-1.8-4-4s1.8-4 4-4s4 1.8 4 4s-1.8 4-4 4");
}

.h1l6k3-kj {
  d: path("M59 35c-23.1 28.1-24.1 6.2-24.1.4c-.1-5.4-.5-21.4-.5-21.4h-4.8s-.4 16-.5 21.4c0 5.8-1 27.7-24.1-.4c0 0-.7 9.1 16 20.3C26.6 59 32 62 32 62s5.4-3 11-6.7C59.7 44.1 59 35 59 35");
}

.rp6uw8keb {
  d: path("M3.8 27S.1 42.2 3.5 44.8c2.2 1.6 3.4-6.3 3.4-6.3s4.2 2.1 5.1-.1c.8-2.3-3.4-2.4-8.2-11.4m56.4 0s3.7 15.2.3 17.8c-2.2 1.6-3.4-6.3-3.4-6.3s-4.2 2.1-5.1-.1c-.8-2.3 3.4-2.4 8.2-11.4");
}

.s7u4i-btv {
  fill: var(--svg-color--b2c1c0, #b2c1c0);
}

.w4ndvlyfw {
  fill: var(--svg-color--62727a, #62727a);
  d: path("M40 21.1c0-.3-3.6 0-8-.1c-4.4 0-8-.2-8 .1s3.5 1 8 .9c4.5 0 8-.7 8-.9");
  opacity: var(--svg-opacity--0-5, 0.5);
}

.yqdljvgzf {
  fill: var(--svg-color--62727a, #62727a);
  d: path("M34.5 20c-.1-3.4-.1-6-.1-6h-4.8s-.1 2.6-.1 6z");
  opacity: var(--svg-opacity--0-5, 0.5);
}

</style>
