<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":48,"height":48};
const content = `<g class="y9tr6bcfx"><circle class="nnrkv4b-h"/><circle class="k6_n5dbum"/><path class="motf62hmo"/><circle class="fd_hk9bdo"/><circle class="aqso4rr0e"/></g><path class="ot8kl2uij"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="arcticons:hill-climb-2" /></template>
<style>
.aqso4rr0e {
  cx: 36.042px;
  cy: 20.618px;
  r: 1.492px;
}

.fd_hk9bdo {
  cx: 21.861px;
  cy: 34.799px;
  r: 1.492px;
}

.k6_n5dbum {
  cx: 36.042px;
  cy: 20.618px;
  r: 5.373px;
}

.motf62hmo {
  d: path("m25.66 31l6.582-6.582m-14.181 14.18l-.981.982l-8.271-5.625L5.5 20.287L16.567 9.22l12.717 4.259l5.652-5.651l2.989 1.757L42.5 14.16l-2.659 2.659m-10.557-3.34L8.809 33.955M5.5 20.287l7.097 9.88");
}

.nnrkv4b-h {
  cx: 21.861px;
  cy: 34.799px;
  r: 5.373px;
}

.ot8kl2uij {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
  d: path("M37.2 34.822a2.653 2.653 0 0 1 3.176-2.6c1.111.214 1.999 1.175 2.11 2.302c.082.837-.183 1.664-.762 2.172c-1.072.94-4.524 3.476-4.524 3.476h5.3");
}

.y9tr6bcfx {
  fill: none;
  stroke: currentColor;
  stroke-linecap: round;
  stroke-linejoin: round;
}

</style>
