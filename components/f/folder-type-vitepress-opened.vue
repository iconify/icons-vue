<script setup>
import { Icon } from '@iconify/css-vue';

const props = defineProps(["width","height"]);

const viewBox = {"width":32,"height":32};
const content = `<defs><linearGradient id="SVGfWAXJvtN" x1="6.482" x2="39.05" y1="1.976" y2="48.206" gradientUnits="userSpaceOnUse"><stop offset="0" class="sz7be0bvx"/><stop offset="1" class="cs-eh8b6j"/></linearGradient><linearGradient id="SVGMPSoKdwh" x1="11.885" x2="26.725" y1="16.427" y2="31.418" gradientUnits="userSpaceOnUse"><stop offset="0" class="bwkdhox2i"/><stop offset="1" class="zdytijs1i"/></linearGradient><linearGradient id="SVGJDgPhPxj" x1="21.814" x2="26.246" y1="13.705" y2="28.807" gradientUnits="userSpaceOnUse"><stop offset="0" class="rwfxvpb_h"/><stop offset=".083" class="g42qkjuof"/><stop offset="1" class="bgjt_ibpq"/></linearGradient></defs><path class="igbq8_b9j"/><path fill="url(#SVGfWAXJvtN)" transform="translate(11.917 10)scale(.41667)" class="ga5tpib1e"/><path class="tti7i2gxb"/><path fill="url(#SVGMPSoKdwh)" transform="translate(11.917 10)scale(.41667)" class="hfp4lbcpe"/><path fill="url(#SVGJDgPhPxj)" transform="translate(11.917 10)scale(.41667)" class="fshji3b8i"/>`;
</script>
<template><Icon :width="width" :height="height" :viewBox="viewBox" :content="content" fallback="vscode-icons:folder-type-vitepress-opened" /></template>
<style>
.bgjt_ibpq {
  stop-color: var(--svg-color--ffa800, #ffa800);
}

.bwkdhox2i {
  stop-color: var(--svg-color--41d1ff, #41d1ff);
}

.cs-eh8b6j {
  stop-color: var(--svg-color--bd36ff, #bd36ff);
}

.fshji3b8i {
  d: path("m27.025 12.576l-7.09 2.467a.27.27 0 0 0-.18.28l.637 7.74c.015.183.198.3.367.235l1.964-.758a.273.273 0 0 1 .367.273l-.18 3.078c-.012.207.2.353.385.266l1.2-.561a.272.272 0 0 1 .384.267l-.294 4.835c-.018.303.39.41.516.134l.084-.183l4.245-12.847c.07-.215-.133-.42-.345-.347l-2.033.7a.273.273 0 0 1-.357-.298l.687-4.982a.273.273 0 0 0-.357-.299");
}

.g42qkjuof {
  stop-color: var(--svg-color--ffdd35, #ffdd35);
}

.ga5tpib1e {
  d: path("M5.036 7.878c-.283-2.038 1.12-3.923 3.133-4.21L33.684.037c2.013-.287 3.874 1.134 4.157 3.172l5.123 36.913c.283 2.039-1.12 3.924-3.133 4.21l-25.515 3.632c-2.013.286-3.874-1.134-4.157-3.173z");
}

.hfp4lbcpe {
  d: path("m33.186 14.92l-7.335 19.238a.538.538 0 0 1-.933.134L12.335 17.834c-.282-.368-.013-.9.446-.881l10.125.408a.5.5 0 0 0 .19-.027L32.51 14.2c.434-.145.841.288.677.72z");
}

.igbq8_b9j {
  fill: var(--svg-color--dcb67a, #dcb67a);
  d: path("M27.4 5.5h-9.2l-2.1 4.2H4.3v4H.5l3.8 12.8h25.2v-21Zm-7.2 2.1h7.1v2.1h-8.1Zm5.5 6.1H6.6v-1.9h20.8v7.626Z");
}

.rwfxvpb_h {
  stop-color: var(--svg-color--ffea83, #ffea83);
}

.sz7be0bvx {
  stop-color: var(--svg-color--49c7ff, #49c7ff);
}

.tti7i2gxb {
  fill: var(--svg-color--fff, #fff);
  d: path("M14.775 13.175a.775.775 0 0 1 .653-.878l10.63-1.513a.77.77 0 0 1 .867.661l2.134 15.38a.775.775 0 0 1-.652.878l-10.632 1.513a.77.77 0 0 1-.866-.66z");
}

.zdytijs1i {
  stop-color: var(--svg-color--bd34fe, #bd34fe);
}

</style>
