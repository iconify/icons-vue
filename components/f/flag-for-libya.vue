<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="o0_5iei5x"/><path class="zwnlajb7y"/><path class="uoe6jwbnn"/><g class="n1mjunbsu"><path class="vwb73lblw"/><path class="f2rh5ybxe"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione:flag-for-libya" /></template>
<style>
.f2rh5ybxe {
  d: path("M32.8 40c-4.4 0-7.9-3.6-7.9-8s3.5-8 7.9-8c1.7 0 3.2.5 4.5 1.4a9.78 9.78 0 0 0-7.4-3.4c-5.5 0-9.9 4.5-9.9 10s4.4 10 9.9 10c3 0 5.6-1.3 7.4-3.4c-1.2.9-2.8 1.4-4.5 1.4");
}

.n1mjunbsu {
  fill: var(--svg-color--fff, #fff);
}

.o0_5iei5x {
  fill: var(--svg-color--3e4347, #3e4347);
  d: path("M2 32c0 5.9 1.7 11.4 4.6 16h50.7c2.9-4.6 4.6-10.1 4.6-16s-1.7-11.4-4.6-16H6.6C3.7 20.6 2 26.1 2 32");
}

.uoe6jwbnn {
  fill: var(--svg-color--83bf4f, #83bf4f);
  d: path("M6.6 48c5.3 8.4 14.7 14 25.4 14s20.1-5.6 25.4-14z");
}

.vwb73lblw {
  d: path("M38.2 36.7v-3.6L34.7 32l3.5-1.1v-3.6l2.2 2.9l3.6-1.1l-2.2 2.9l2.2 2.9l-3.6-1.1z");
}

.zwnlajb7y {
  fill: var(--svg-color--c94747, #c94747);
  d: path("M57.4 16C52.1 7.6 42.7 2 32 2S11.9 7.6 6.6 16z");
}

</style>
