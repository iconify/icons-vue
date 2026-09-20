<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":256,"height":256};
const content = `<path class="moyhp_b_y"/><path class="aj03n6epd"/><path class="bzz905b-m"/><path class="kk3hv2bqr"/><path class="m8zkei_3l"/><path class="ci5dzby7y"/><path class="xktt7kl-m"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="logos:gleam" /></template>
<style>
.aj03n6epd {
  fill: var(--svg-color--f3852f, #f3852f);
  d: path("M256 181.019L181.019 256l-1.145-.881l-52.309-123.609L128 128z");
}

.bzz905b-m {
  fill: var(--svg-color--f2c32e, #f2c32e);
  d: path("m128 128l-2.828 1.943l-50.636 123.898l.445 2.159h106.038z");
}

.ci5dzby7y {
  fill: var(--svg-color--69c5e5, #69c5e5);
  d: path("M74.981 0L0 74.981L128 128l.225-3.256L80.496 3.026z");
}

.kk3hv2bqr {
  fill: var(--svg-color--cbdc38, #cbdc38);
  d: path("m0 181.019l3.174-2.468l121.998-51.002L128 128L74.981 256z");
}

.m8zkei_3l {
  fill: var(--svg-color--b5d66d, #b5d66d);
  d: path("m0 74.981l3.174-.215l123.071 50.473L128 128L0 181.019z");
}

.moyhp_b_y {
  fill: var(--svg-color--f36a22, #f36a22);
  d: path("M256 74.981v106.038l-3.417.333l-123.367-51.822L128 128z");
}

.xktt7kl-m {
  fill: var(--svg-color--6d9fd5, #6d9fd5);
  d: path("M74.981 0h106.038L128 128z");
}

</style>
