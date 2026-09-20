<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="v28gy8bmp"/><path class="zfxfur4fe"/><path class="vn6i86eyj"/><path class="d-oubcc7x"/><path class="vzffdi6fz"/><path class="bfxq9ub5k"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:html5-boilerplate" /></template>
<style>
.bfxq9ub5k {
  fill: var(--svg-color--304a51, #304a51);
  d: path("m62.095 209.618l52.875-37.822l18.535 13.736l-49.96 35z");
}

.d-oubcc7x {
  fill: var(--svg-color--304a51, #304a51);
  d: path("m156.34 142.239l22.486 11.044l54.42-39.518l-22.486-11.975z");
}

.v28gy8bmp {
  fill: var(--svg-color--222, #222);
  d: path("M0 0h256v256H0z");
}

.vn6i86eyj {
  fill: var(--svg-color--466770, #466770);
  d: path("m117.228 34.336l22.768 10.726l19.005 51.937h-18.817L117.228 34.34");
}

.vzffdi6fz {
  fill: var(--svg-color--466770, #466770);
  d: path("m156.308 142.198l22.518 11.035l21.289 68.839l-23.285-11.842l-20.522-68.03");
}

.zfxfur4fe {
  fill: var(--svg-color--e08524, #e08524);
  d: path("M114.406 35.277L91.827 99.82l-68.494.189l55.51 41.021l-19.948 66.233l56.075-39.7l57.584 42.147l-21.079-68.869l54.948-41.021l-68.306.189z");
}

</style>
