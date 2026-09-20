<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":224};
const content = `<defs><linearGradient id="SVGuEZCqbgq" x1="47.952%" x2="47.952%" y1="97.595%" y2="0%"><stop offset="0%" class="sc9knx3mp"/><stop offset="61.372%" class="hjxed1hvm"/><stop offset="100%" class="pvxm2_b2q"/></linearGradient></defs><path class="wpbcr6bue"/><path fill="url(#SVGuEZCqbgq)" class="r23jpcl7r"/><path class="sbiw54vlf"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:hyper" /></template>
<style>
.hjxed1hvm {
  stop-color: var(--svg-color--dc3939, #dc3939);
}

.pvxm2_b2q {
  stop-color: var(--svg-color--ff1bb4, #ff1bb4);
}

.r23jpcl7r {
  d: path("M7.175 14.35v194.583a7.18 7.18 0 0 0 7.178 7.175h227.294a7.175 7.175 0 0 0 7.178-7.175V14.35a7.18 7.18 0 0 0-7.178-7.175H14.353a7.175 7.175 0 0 0-7.178 7.175M0 14.35C0 6.425 6.424 0 14.353 0h227.294C249.574 0 256 6.427 256 14.35v194.583c0 7.925-6.424 14.35-14.353 14.35H14.353C6.426 223.283 0 216.856 0 208.933z");
}

.sbiw54vlf {
  fill: var(--svg-color--fff, #fff);
  d: path("M76.15 83.31h38.486v7.473H76.149zM64.406 63.947L30.52 94.393l10.547-26.645l-14.887-10.04l33.885-30.443l-11.47 28.345z");
}

.sc9knx3mp {
  stop-color: var(--svg-color--ffb300, #ffb300);
}

.wpbcr6bue {
  d: path("M13.18 4.5h229.64c4.517 0 8.18 3.655 8.18 8.163v197.674c0 4.508-3.663 8.163-8.18 8.163H13.18c-4.517 0-8.18-3.655-8.18-8.163V12.663C5 8.155 8.663 4.5 13.18 4.5");
}

</style>
