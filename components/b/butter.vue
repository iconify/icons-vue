<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":36,"height":36};
const content = `<path class="ttt6q9bkg"/><path class="dn_zz9npx"/><path class="n34t0db8p"/><path class="y_15_lbrc"/><path class="q1v9gqb7v"/><path class="ndihr16vr"/><path class="mcz_w6jdf"/><path class="da_drc3ms"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="twemoji:butter" /></template>
<style>
.da_drc3ms {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M17.182 28.302V26.29l-7 4.059L10 32.378z");
}

.dn_zz9npx {
  fill: var(--svg-color--ccd6dd, #ccd6dd);
  d: path("m35.145 20.344l-22.86 13.219c-.902.521-2.364.521-3.266 0L.855 28.842c-.902-.521-.902-1.367 0-1.888l22.86-13.219c.902-.521 2.364-.521 3.266 0l8.164 4.721c.901.521.901 1.367 0 1.888");
}

.mcz_w6jdf {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M17.182 28.302V26.29l-7 4.059L3 26.325v2.012l7 4.041z");
}

.n34t0db8p {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M33 19.011v-8.083l-7-4.041l-13.042 7.502v8.083l7 4.042z");
}

.ndihr16vr {
  fill: var(--svg-color--ffe8b6, #ffe8b6);
  d: path("M17.182 28.302V26.29l-7-4.041L3 26.325v2.012l7 4.041z");
}

.q1v9gqb7v {
  fill: var(--svg-color--ffcc4d, #ffcc4d);
  d: path("M33 19.011v-8.083l-13.042 7.503v8.083z");
}

.ttt6q9bkg {
  fill: var(--svg-color--99aab5, #99aab5);
  d: path("m35.145 22.16l-22.86 13.219c-.902.521-2.364.521-3.266 0L.855 30.658c-.451-.261-.676-.602-.676-.944v-1.843l23.535-12.32c.902-.521 2.364-.521 3.266 0l8.84 3.819c0 .558-.005 1.497 0 1.834c.006.345-.219.692-.675.956");
}

.y_15_lbrc {
  fill: var(--svg-color--ffd983, #ffd983);
  d: path("M33 19.011v-8.083l-13.042 7.503l-7-4.042v8.083l7 4.042z");
}

</style>
