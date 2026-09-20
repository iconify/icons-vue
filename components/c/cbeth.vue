<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":24,"height":24};
const content = `<g class="f124h_b3v"><path class="gydkznbhr"/><path class="dite-ccgw"/><path class="s73pnobgb"/><path class="tm0m5frxm"/><path class="ov-ccsboe"/><path class="zme_xkl4l"/><path class="b4hzduwod"/></g>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="token-branded:cbeth" /></template>
<style>
.b4hzduwod {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M8.063 11.837L12 14.188v-4.157z");
}

.dite-ccgw {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M12 5.25v4.781l3.938 1.806z");
}

.f124h_b3v {
  fill: var(--svg-color--0052ff, #0052ff);
}

.gydkznbhr {
  d: path("M12 20.156a8.157 8.157 0 1 0 0-16.313a8.157 8.157 0 0 0 0 16.313M21 12a9 9 0 1 1-18 0a9 9 0 0 1 18 0");
}

.ov-ccsboe {
  d: path("M12 18.188v-3.252l-3.937-2.345z");
}

.s73pnobgb {
  d: path("m12 5.25l-3.937 6.587l3.937-1.8z");
}

.tm0m5frxm {
  fill-opacity: var(--svg-fill-opacity--0-6, 0.6);
  d: path("M12 14.936v3.252l3.938-5.597z");
}

.zme_xkl4l {
  fill-opacity: var(--svg-fill-opacity--0-2, 0.2);
  d: path("m12 14.188l3.938-2.352l-3.938-1.8z");
}

</style>
