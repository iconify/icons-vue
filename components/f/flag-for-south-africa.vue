<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="zziul1bpw"/><path class="ech0v-brq"/><path class="jve4r_bxo"/><path class="fy-iq6zsp"/><path class="qvo8p5are"/><path class="ajm_ub6vs"/><path class="dsxmy5brs"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-south-africa" /></template>
<style>
.ajm_ub6vs {
  fill: var(--svg-color--ffce31, #ffce31);
  d: path("M5.3 18.4c-.1.2-.2.4-.3.7c-.5 1.1-1 2.2-1.4 3.4l9.6 9.5l-9.6 9.5c.4 1.2.8 2.3 1.4 3.4c.1.2.2.4.3.7L19 32z");
}

.dsxmy5brs {
  fill: var(--svg-color--fff, #fff);
  d: path("M31.7 40L14.8 56.6c.3.2.7.5 1 .7c.8.5 1.6 1 2.5 1.4l15.1-14.8h26.1c.4-1 .8-2 1.2-3.1c.1-.3.1-.5.2-.8z");
}

.ech0v-brq {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M3.5 22.5c-1 3-1.5 6.2-1.5 9.5s.5 6.5 1.5 9.5l9.6-9.5z");
}

.fy-iq6zsp {
  fill: var(--svg-color--ed4c5c, #ed4c5c);
  d: path("M59.5 20.1C54.9 9.4 44.3 2 32 2c-4.9 0-9.6 1.2-13.7 3.3l15.1 14.8z");
}

.jve4r_bxo {
  fill: var(--svg-color--428bc1, #428bc1);
  d: path("M18.3 58.7C22.4 60.8 27.1 62 32 62c12.3 0 22.9-7.4 27.5-18.1H33.4z");
}

.qvo8p5are {
  fill: var(--svg-color--fff, #fff);
  d: path("M60.5 22.7c-.3-.9-.6-1.8-1-2.6H33.4L18.3 5.3c-.7.3-1.3.7-2 1.1c-.5.3-1 .7-1.5 1L31.7 24h29.2c-.1-.4-.2-.9-.4-1.3");
}

.zziul1bpw {
  fill: var(--svg-color--699635, #699635);
  d: path("M60.9 40c.7-2.5 1.1-5.2 1.1-8s-.4-5.5-1.1-8H31.7L14.8 7.4c-4 2.8-7.3 6.6-9.6 11L19 32L5.3 45.6c2.2 4.4 5.5 8.2 9.6 11L31.7 40z");
}

</style>
