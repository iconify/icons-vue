<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":64,"height":64};
const content = `<path class="wh8z86h3s"/><path class="lva-abngf"/><path class="y8-xnzq0g"/><path class="yk5qctbqs"/><path class="fvd60oqvy"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="emojione-v1:flag-for-flag-seychelles" /></template>
<style>
.fvd60oqvy {
  fill: var(--svg-color--009543, #009543);
  d: path("M54 54c6.564 0 9.932-4.835 9.994-10.831L7.001 53.59c.912.258 1.903.41 2.999.41z");
}

.lva-abngf {
  fill: var(--svg-color--003f87, #003f87);
  d: path("M18.2 10H10C3.373 10 0 14.925 0 21v22c0 2.773.711 5.3 2.105 7.235L24.2 10z");
}

.wh8z86h3s {
  fill: var(--svg-color--f9cb38, #f9cb38);
  d: path("M24.2 10L2.11 50.23c.322.447.693.853 1.09 1.231L50.87 9.995H24.205");
}

.y8-xnzq0g {
  fill: var(--svg-color--ec1c24, #ec1c24);
  d: path("M64 21c0-6.075-3.373-11-10-11h-3.135L3.195 51.467a8.8 8.8 0 0 0 1.868 1.355L64 30.461z");
}

.yk5qctbqs {
  fill: var(--svg-color--e6e7e8, #e6e7e8);
  d: path("M64 43V30.461L5.063 52.822a9.4 9.4 0 0 0 1.938.768l56.993-10.421c0-.057.006-.112.006-.169");
}

</style>
