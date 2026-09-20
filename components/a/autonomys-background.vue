<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="ft5dv1b6b"><g clip-path="url(#SVGHcSWxdhd)"><path class="mumfproca"/><path class="sz6xf-g2m"/><path class="ybac7gy2g"/><path class="oz69krb0l"/><path class="co8_3rr3e"/><path class="o74am9ajn"/></g><defs><clipPath id="SVGHcSWxdhd"><path class="py7ktqbvf"/></clipPath></defs></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:autonomys-background" /></template>
<style>
.co8_3rr3e {
  fill: var(--svg-color--fff, #fff);
  d: path("M4 11.87c0 .77.106 1.515.302 2.22L9.984 4C6.543 4.909 4 8.088 4 11.87m11.802 2.207L12 7.326l-3.8 6.75z");
}

.ft5dv1b6b {
  fill: none;
}

.mumfproca {
  fill: var(--svg-color--000, #000);
  d: path("M24 0H0v24h24z");
}

.o74am9ajn {
  fill: var(--svg-color--fff, #fff);
  d: path("M15.802 14.077L12 7.326l-3.8 6.75z");
}

.oz69krb0l {
  fill: var(--svg-color--fff, #fff);
  d: path("M12 20a7.92 7.92 0 0 0 5.744-2.471H6.256A7.92 7.92 0 0 0 12 20m-8-8.13c0 .77.106 1.515.302 2.22L9.984 4C6.543 4.909 4 8.088 4 11.87");
}

.py7ktqbvf {
  fill: var(--svg-color--fff, #fff);
  d: path("M0 0h24v24H0z");
}

.sz6xf-g2m {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.016 4l5.682 10.09A8.3 8.3 0 0 0 20 11.87c0-3.782-2.542-6.961-5.985-7.87");
}

.ybac7gy2g {
  fill: var(--svg-color--fff, #fff);
  d: path("m14.016 4l5.682 10.09A8.3 8.3 0 0 0 20 11.87c0-3.782-2.542-6.961-5.985-7.87M12 20a7.92 7.92 0 0 0 5.744-2.471H6.256A7.92 7.92 0 0 0 12 20");
}

</style>
