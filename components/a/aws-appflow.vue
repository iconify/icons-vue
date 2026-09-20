<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<defs><linearGradient id="SVGyDrnJbhE" x1="0%" x2="100%" y1="100%" y2="0%"><stop offset="0%" class="i__ch2t6w"/><stop offset="100%" class="r7ikv4bnu"/></linearGradient></defs><path fill="url(#SVGyDrnJbhE)" class="tmbkaq7lv"/><path class="jw3u0vbdc"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:aws-appflow" /></template>
<style>
.i__ch2t6w {
  stop-color: var(--svg-color--b0084d, #b0084d);
}

.jw3u0vbdc {
  fill: var(--svg-color--fff, #fff);
  d: path("m133.302 60.8l-50.22 84.438l-3.322-12.39l-6.18 1.658l6.254 23.34l23.34-6.256l-1.654-6.179l-13.2 3.533l48.62-81.74h48.049l24.019 41.596l-24.02 41.6h-25.106v6.403h28.8l27.715-48.003l-27.715-48zm15.63 43.61l1.657 6.182l13.353-3.58l-46.134 81.791h-48L45.788 147.2l24.02-41.6h19.677v-6.397h-23.37L38.4 147.2l27.715 48h55.43l47.533-84.26l3.27 12.212l6.183-1.658l-6.256-23.337z");
}

.r7ikv4bnu {
  stop-color: var(--svg-color--ff4f8b, #ff4f8b);
}

.tmbkaq7lv {
  d: path("M0 0h256v256H0z");
}

</style>
